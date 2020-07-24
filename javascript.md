**Diff between var and let**

********************************************************

The  _var_ Keyword declares a variable to be a part of the program, and optionally allows you to give an initial value.



The  _let_  Keyword allows more limited access to the variable than the  _var_  keyword



_var_  adult=True;



if (adult){

​	var name="Filius-Fall";

​	age=21;

}

console.log(name);   --> Filius-Fall

console.log(age) ;  --> Error



The attempt to access age is not possible outside of  _if_ bcs age was **block scoped** where as _name_ wasnt.



*******************************************************************************************************



## const

 they are unchangeable it is not recommended to use this for object values bcs those can be changed but the variable cant be **reassigned**  

`const names = ['filus','fall'];`

`names[2] = "rams";`

`names = []  //not defined`







 





