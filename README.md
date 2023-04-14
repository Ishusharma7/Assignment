  Difference between for/in and for/of loops
  
  for/in                                           for/of


loop through arrays and objects			loop through arrays,map,set,arguments object

itterates over property name                     iterater over property value      


			                         	In arrays

 			const rgb = ['red','green','blue']

output-->log '0','1','2'			output --> log 'red','green','blue'


                     HOISTING


javascript executes after two passes where in first pass it moves all the declarations to top and then executes the program this is known as hoisting

let, const and var ---->  let and const are hoisted to the top of the code in time of execution but are not intialised which means javascript is aware of the variable but not intialise (we can call the code between top block and declared space of let or const as detention zone) them until they are declared but with var its declaration is also moved at the top of the code but its intialisation is not which is why it does not give any reference error but only undefined variable.

regular funnction  and function expression --->  As regular functions are only declaration of functions so when they are hoisted and moved they run wherever javascrpt places them whereas function expressions are contained int a declared variale which blocks them from being intialised at the top which is we cant create them unless they are declared.
