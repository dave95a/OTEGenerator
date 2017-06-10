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
 
var object = {
    element: ["div",
        "div"
    ]
    style: ["height:8em;width:8em;background-color:red;",
        "height:10em;width:10em;background-color:blue;"
    ],
    bodyfunc: ["function body1(){alert('This is a body function')}",
        "function body2(){alert('This is a body function')}"
    ],
    elementfunc: ["function element1(){alert('This is a element function')}",
        "function element2(){alert('This is a element function')}"
    ]
};
