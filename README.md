JavaScript OOP Concepts

- A namespace called Animal. Two sub classes from the namespace, one called Cat and another called Dog. 
- Two classes, one called Cat and another called Dog. The Cat class is created using literal notation and the Dog class is created using constructor notation.
- A new instance of the Cat class is created. Directly underneath,a new instance of the Dog class is created.
- A new class using constructor notation called Animal is created. When a new instance of the Animal class is created, the message “The Animal has been created” is displayed in the console window.
- The same step is done using constructor notation instead. The class accepts a parameter and that value is what is displayed in the console window. The message is passed as an argument into the constructor at the moment that the Animal class is instantiated.
- A new class using constructor notation called Animal is created. Five properties within your class are defined: type, breed, color, height, and length. These properties are set in the constructor and parameters are passed into the function’s constructor. The properties are set, and then the actual arguments are passed in during the object’s instantiation.
- A for-in loop to is used to loop through and display all of the properties in the Animal class and are displayed within the console window.
- A public method called speak is created. Within the speak method a conditional is used to check the type of Animal being created. If it’s a dog, “The <color> dog is barking!” will be returned. If it’s a cat, “The <color> cat is meowing!” will be returned instead. That method will be called after the Animal class has been instantiated.
- All properties are converted to private properties. A private method called checkType() is created to check what type it is. If it’s dog, dog will be returned, otherwise, cat will be returned. Then, a public method called speak is created that returns the value of the checkType() method. The console window will display “The <animal type> has made a noise!”
- A String method called findWords() is created that inherits from the native String Object. This method will find all instances of a specific word within a provided paragraph of text. It will then alert out to the user the number of times that word was found in the paragraph.

Oil Change

An application that determines whether or not your vehicle needs an oil change. If it does, it will alert the user of the fact within the console window.

- An abstract base class called Vehicle is created that accepts four parameters including make (string), model (string), total miles (number), and the mileage for the last oil change (number).
- Within the Vehicle class, 6 public properties named make, model, totalMiles, drivenMiles, type, and lastOilChange are created. The make, model, totalMiles, and lastOilChange properties are initialized with their respective arguments. The drivenMiles property is initialized to 0 and the type property is initialized to an empty string.
- A public method called drive() is created that accepts a parameter (miles). The public drivenMiles property is incremented and set to the miles argument and the method is returned.
- A public method called checkOil() is created. Within this method the following check is performed: the total miles minus the last oil change plus the driven miles are less than or equal to 3000. If they are, a message to the user that they need an oil change is returned.
- A new sub class called Car is created that accepts one parameter for the amount of doors that the car has. 
- A public property called doorCount is initialized within the Car class and is set equal to the argument.
- Within the Car a conditional is used to check and see if the door count is greater than 2. If it is, the type property is set to Sedan. Otherwise, it is set to coupe.
- The Car class inherits from the Vehicle base class and the make, model, total miles, and last oil change values is passed into the Vehicle’s constructor. 
- A new instance of the Car class is created and the number of doors that the car has is passed into the Car’s constructor.
- Method chaining is used to call the drive() method of the car object, passing in a numeric value as a parameter. At the same time, the checkOil() method is called. The results are displayed in the console window. You will get a message indicating your car needs an oil change or you will get the object hierarchy.

The Recipe Card

An object to hold information on your favorite recipe is created. It has properties for title (a string), servings (a number), and ingredients (an array of strings). The object has a publically available method that when called, will log out the recipe within the console so that the recipe information looks like this:

- Guacamole
- Serves: 4
- Ingredients: 
- 3 Avocados
- 1 Lime
- 1 Teaspoon Salt
- 1/2 Cup Onion
- 3 Tablespoons Cilantro
- 2 Diced Tomatoes
- 1 Teaspoon Garlic
- 1 Pinch Ground Pepper

The Reading List

This will keep track of which books you read and which books you want to read! An array of objects is created, where each object describes a book and has properties for the title (a string), author (a string), and alreadyRead (a boolean indicating if you read it yet). The array of books will be iterated through. For each book, the book title and book author will be logged such as: "The Hobbit by J.R.R. Tolkien". Then, a conditional is used to change the output depending on whether you read it yet or not. If you read it, 'You already read "The Hobbit" by J.R.R. Tolkien' will be displayed, and if not, 'You still need to read "The Lord of the Rings" by J.R.R. Tolkien.' will be dispalyed in the log.
