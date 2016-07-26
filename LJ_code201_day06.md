# LJ Code 201 Day - 6

“Tell me and I forget Teach me and I remember. Involve me and I learn.”


Today, the discussion talked about Domain Modeling.

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. 
¥	Communication tool- a well-articulated model can be used by stakeholders—coders and business types alike— to better understand the problem at hand.

The problem domain is often considered the hardest part of coding. You have a problem. How do you define it? How do you construct your plan of attack? How do you build the framework for your solution? If you can’t break your problem down into the individual coding tasks, you will likely be overwhelmed by it. If you can break your big problem down into little itty bitty problems, you can tackle those one by one, and solve the big problem. 
¥	You can often make the problem domain easier by cutting out edge cases and narrowing your focus to a particular part of the problem

In JS, an object is a collection of properties (attributes, or ‘adjectives’) and methods (behaviors, or ‘verbs'). Today, we will use objects to serve as our conceptual models, which we will describe as a collection of properties and methods. This is referred to as Object Oriented Programming (OOP). 

•	Two ways to make a object to render things.

 There are two ways to make an object to model things:
¥	Object literals
   var hotel = {
     name: ‘Name’,
     rooms: 40,
     booked: 25,
     checkAvailability: function() {
     return this.rooms - this.booked;
     }
};

Object constructors (write a function that encompasses the object, its properties, and its methods)
  function Hotel(name, rooms, booked) {
     this.name = name;
     this.rooms = rooms;
     this.booked = booked;
     this.checkAvailability: function() {
        return this.rooms - this.booked;
      };
};

 var quayHotel = new Hotel(‘Quay’, 40, 25);
                     
Built in Objects

There are a lot of objects built in to javascript, and into the browser. 
¥	document.[thousands of potential properties and methods]
¥	window.[thousands of potential properties and methods]
