# OTEGenerator
OTEGenerator stands for ObjectToElementGenerator and makes it possible for the user to easy and fast generate Html elements by specified keys in a object.
 
 This is what the function kan handle as of now
 
	//div,color:#000000;,function Btest(){// DoStuff},function Etest(){// DoStuff}
	var obj = {element:["value"],style:["value"],bodyfunc:["value"],elementfunc:["value"]}
	
	element = "Html element"
	style = "css"
	bodyfunc = "function that is appended to body or just javascript"
	elementfunc = "function that is appended to the element or just javascript"
	
	You can send in x amount of values at any order so 2 divs would equal to {element:["value","value"]}
	and you don't have to use all the keys.
 

