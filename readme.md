#  Javascript
|---------------|----------|----------|
## 1. Javascript - Variables

    //define variable with keyword let <br />
    let firstName = "Darko"; <br />
    let lastName = "Darevski"; <br />

    //let`s print in console <br />
    console.log(firstName, lastName); <br />

    Output <br />
    Darko Darevski <br />
## 2. Constant<br />
   The value of a constant can't be changed through reassignment, and it can't be redeclare<br />

   //define constant<br />

   const number = 43;<br />
   cosnole.log(number);<br />
   // output <br />
   43<br />
## 3. Primitive Types 

    - Boolean <br />
    - Null <br />
    - Undefined <br />
    - Number <br />
    - BigInt <br />
    - String <br />
    - Symbol <br />

    let isAproved = true; <br />
    let chooseColor = null; <br />
    let firstName = undefined; <br />
    let number = 43; <br />
    let lastName = "Darevski"; <br />

## 4. Object 
    Every object has properties and methods

    // Create an object:

    `let car = {
            brand: "toyota",
            model: "corola",
            engine: "hybryd",
            year: 2019
    }`
    // Lets print 
    console.log(car);

    // we can change the values of some property
    // bot notation
    `car.brand = "Honda";`
    // Access  to property
    `console.log(car.brand);`

    // bracket notationt
    car['brand'] = "Honda";
    console.log(car.brand)
 ## 5. Arrays

    // This is empty arrays
    let colors = [];

    let colors = ['blue', 'red', 'green'];
    console.log(colors);
    // output
    
    0: "blue"
​    1: "red"
​    2: "green"

   // We can acces to specific index of a array
   
   console.log(colors[0]);
   // output
   "blue"