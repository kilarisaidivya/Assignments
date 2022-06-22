# Assignments
All the GUVI-ZEN assignments are available in this repository
//a,c
class Movie{
    constructor(title,studio,rating){
        this.tiltle=title;
        this.studio=studio;
        this.rating=rating;
    }
    getpg(arr){
 var res = arr.filter((ele)=>ele.rating=="PG");
 return res;

}
}
var m1 =  new Movie("Casino Royale","def Productions","PG");
var m2 =  new Movie("Royale","abc Productions","PG14");
var m3 =  new Movie("Casino","ghi productions","PG");
var m4 =  new Movie("Casino Royale"," Productions","PG");
const arr=[m1,m2,m3,m4];
// console.log(arr);
console.log(m1.getpg(arr))
  
//The constructor for the class Movie will set the class property rating to "PG" as default when no rating is provided.
  
  class Movie{
    constructor(title,studio,rating){
        this.tiltle=title;
        this.studio=studio;
        this.rating="PG";
    }
    }
   var m1 =  new Movie("Casino Royale","def Productions","PG");
var m2 =  new Movie("Royale","abc Productions","PG14");
var m3 =  new Movie("Casino","ghi productions","PG");
console.log(m1);
console.log(m2);
console.log(m3);

//Write a piece of code that creates an instance of the class Movie with the title “Casino Royale”, the studio “Eon Productions”, and the rating “PG­13”
class Movie{
    constructor(title,studio,rating){
        this.tiltle=title;
        this.studio=studio;
        this.rating=rating;
    }
}
   var m1 =  new Movie("Casino Royale","Eon Productions","PG­13");
   console.log(m1);
   
  --------------------------------------------------------------------------------------------------------------------------------------------------------------------
  //2
  class Circle{
    constructor(radius,color){
        this.radius=radius;
        this.color=color;
    }
   
    getArea(){
        var radiusSquare=this.radius*this.radius;
        return 3.14*radiusSquare;
    }
    getCircumference(){
        return 2*3.14*this.radius;
    }
}
var c1=new Circle(10,20);
console.log(c1.getArea());
console.log(c1.getCircumference());

  
-----------------------------------------------------------------------------------------------------------------------------------------------------
//Write a “person” class to hold all the details.

class Person{
    constructor(fname,lname,age,rollno){
        this.fname=fname;
        this.lname=lname;
        this.age=age;
        this.rollno=rollno;
    }
}

var p1 = new Person("John","doe",23,12345);
console.log(p1);

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

//write a class to calculate uber price.

class Uber{
  constructor(km){
    this.km=km;
    this.price=this.km*5;
  }
  getprice(){
    return this.price}

getdiscount(){
  var discount=(10/100)*this.price;
  var totalprice=this.price-discount;
  return totalprice;}
}
  
var u1=new Uber(10);
console.log(u1.getprice());
console.log(u1.getdiscount());
