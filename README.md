# Javascript-with-InfinitezenCODER
This will be a special one..
<br>
//name,y,$,age,Student,Student2,Profile,a,b,c,d,num,mode,color,Age,Result,
console.log("This is my first  Javascript Program Line.");
let name="InfinitezenCODER";//Always Declare a variable using let.
const pi=3.14;
name="debuugger";//Value of name is changed.
console.log(name);
let y=undefined;
console.log(y);
$="American";//Variable names can be started with $ and _.
{
let age=19;
console.log(age);
}//age variable is block scoped here.
{
let age=20;
console.log(age);
}

const Student=            //Student is object here.
{
 fullName:"SWASTIK PATRA", //This is teh way to write a key.
 age: 19,
 college: "VSSUT",
 Experience: "Fresher", 
};
const Student2=
{
 fullName:"SWASTIK PATRA",
 age: 19,
 Nationality: "Indian",
 Fan : "Zlatan Ibrahimovic",
};
console.log(Student2.Fan);//Way to access the key value.
console.log(Student["age"]);//Another way to access the key value.
Student["age"]= Student["age"]+1;
console.log(Student.age);
Student["age"]= Student["age"]+2;
console.log(Student.age);

const Profile= 
 {
    User_name : "shradhakhapra",
    isFollow : true,
    Posts : 195,
    Followers : 569000 ,
    Following : 4 ,
    Name : "Shradha_Khapra",
    Profession : "Enterpreneur",
    Experience : "Ex-Microsoft DRDO",
    Instituition : "Apnacollege",
    Moto : "TO EDUCATE SOMEONE IS THE HIGHEST PRIVILEGE", 
};


console.log (Profile.Name);
// console.log (Profile ["Experience"]);



// This Part Will Not be Executed.
/* This Part Will not be Executed. */


//Arithmatic Operators
let a = 2;
let b = 4;
console.log("a+b");
console.log(a+b);
console.log("a+b =", a+b);
console.log("a-b =", a-b);
console.log("a*b =", a*b);
console.log("a/b =", a/b);
console.log("a%b =", a%b);
console.log("a**b =", a**b);
console.log("a++=", a++);
console.log("a=", a);
console.log("++a=", ++a);



//Assignment Operators

//Comparison Operators
let c=7, d=8;
console.log("c==d",c==d);
console.log("c!=d",c!=d);
console.log("c===d",c===d);
console.log("c!==d",c!==d);
let e="9";
console.log("d===e",d===e);
console.log("d==e",d==e);


//Logical Operators
let x=9 ;
 y=10;
let cond1 = x>y;
let cond2 = x!=y;
console.log("cond1 && cond2 = ",cond1 && cond2);
console.log("cond1 || cond2 = ",cond1 || cond2);


//Conditional Statements.

//If statement
let age;
if (age>=18)
{
  console.log("You can vote");
}

//If-else statement
let num=5;
if (num%2==0)
{
    console.log("Even number")
}
else{
    console.log("Odd number")
}

//If-Else if statement
let mode="light";
let  color;
if (mode==="dark")
{
    color = "blck";
}
else if(mode==="light")
{
    color="white";
}
else if(mode==="smoggy")
{
    color="grey";
}
else if(mode==="Foggy")
{
    color="light yellow";
}
else{
    color="light green";
}
console.log(color);


//Ternary Operator
let Age=19,Result;
Result= Age>=18 ? "Adult" : "Not Adult"
console.log(Result);






