# Assignments
All the GUVI-ZEN assignments are available in this repository
class Movie{
    constructor(title,studio,rating){
        this.tiltle=title;
        this.studio=studio;
        this.rating=rating;
    }

     constructor(title,studio,rating){
         this.tiltle=title;
       this.studio=studio;
        this.rating="PG";
     }
    getpg(Movie){
        var output=[];
        for(let i=0;i<Movie.length;i++){
            if(Movie[i].rating==="PG"){
                output.push(Movie[i]);
            }
        }
        return output;
    }

}
    var m1 =  new Movie("Casino Royale","Eon Productions","PG.13");
    var m2 =  new Movie("Casino Royale","Eon Productions","PG");
    var m3 =  new Movie("Casino Royale","Eon Productions","PG");
    var m4 =  new Movie("Casino Royale","Eon Productions","PG");
    
  console.log(getpg[m1,m2,m3,m4]);
  
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  
  class Circle{
    Circle(radius){
        this.radius=radius;
    }
    Circle(radius,color){
        this.radius=radius;
        this.color=color;
    }
    getradius(){
        return this.radius;
    }
    setradius(radius){
        return radius;
    }
    getcolor(){
        return this.color;
    }
    setcolor(color){
        return color;
    }
    toString(){

    }
    getArea(){
        var radiusSquare=this.radius*this.radius;
        return 3.14*radiusSquare;
    }
    getCircumference(){
        return 2*3.14*this.radius;
    }
}
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
