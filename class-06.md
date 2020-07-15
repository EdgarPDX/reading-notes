Reading
Understanding the problem domain is the hardest part of programming
From the Duckett JS book

Chapter 3: “Object Literals” (pp.100-105)
    -In an object, Variables become known as properties
    -In an object functions become known as methods
        -Methods represent tasks that are associated with the objec
    -The value of a property can be a string, number, boolean, array or another object
    Literal notation,
        var hotel = {
            name: 'Quay'
            rooms: 40,
            booked: 25,
            check availability: function(){
                return this.room - this.booked;
            }
        }

        "this.()" is a keyword that indicates that it is using properties in the same object
        Dot Notation
        -var hotelName = hotel.name
        -var roomFree = hotel.checkavailability();

Chapter 5: “Document Object Model” (pp.183-242)