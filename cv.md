# Irina Nesterova
*Junior Front-end Developer*

Odessa, Ukraine  
[social](https://www.linkedin.com/in/irina-nesterova-7809481b4)  
<irina.vprincipe@gmail.com>

## SKILLS: 
- HTML5 
- CSS/SCSS
- Bootstrap
- Grid
- Flexbox
- Adaptive Coding 
- VSCode
- Figma
- BEM
- Jquery
- Git
- JavaScript

## Education
**Computer School Hillel(IT School)** - *Course Front-End Basic*  
(04.2020-07.2020)

**Computer School Hillel(IT School)** - *Course Front-End Pro*  
(08.2020 - 02.2021)

## Code Example
```
//цепочка прототипов с помощью функций конструкторов

function Cars(make, model, year) {
    this.make = make;
    this.model = model;
    this.year = year;
}

function Chery(make, model, year, money) {
    Cars.apply(this, arguments);
    this.money = money;
}

Cars.prototype.startYear = function() {
    return (`Tesla start ${this.model} ${this.year}`);
};

Chery.prototype = Object.create(Cars.prototype, {
    color: {
        value: "red"
    }
});

Chery.prototype.startDrive = function() {
    return (`Model cost ${this.money}`);
}

let tesla = new Cars("Germany", "Standart", 2007);
let honda = new Cars("Japan", "Accord", 2003);
let chery = new Chery("China", "Tiggo", 2008, 15000);
```

## About Me
I'm always open to learning new things.
## Languages   
- Ukranian \-native\-
- Russian \-native\-
- English \-A2\-
