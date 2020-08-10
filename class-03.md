

## Table of Contents

- [Day 1](class-01.md)
- [Day 2](class-02.md)
- [Day 3](class-03.md)
- [Day 4](class-04.md)
- [Day 5](class-05.md)
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]
- [TBD]

## Day Three Notes: Reading
From the Duckett HTML book:

Chapter 3: “Lists” (pp.62-73)
Chapter 13: “Boxes” (pp.300-329)
From the Duckett JS book:

Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)
Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182

# Box dimensions

  in CSS div {

            border: 2px solid black line;

            height: 300px;

            width: 400px;

            background-color: #ee3e80;]}
        
# Placement

  in CSS [selector] {
                  float: center;
                  padding: 5px;
                  margin: 0 px;}

![screenshot of demo](images/Screenshot_(490).png)
![screenshot of demo](images/Screenshot_(491).png)

# Loops

var mytool= 'hammer';

var mytoolshed= ['miter saw', 'band saw', 'drill press', 'table saw', 'planer', 'saw legs', 'impact drill'];

console.log('Challenge 1');

for(var i=0; i < mytoolshed.length; i++){

  console.log('the value of i is ' + i);

  console.log('the value of my array is ' + mytoolshed[i]);
}

console.log (mytoolshed);

console.log('Challenge 2');

var i = 0;

while(i< mytoolshed.length){

  if(mytoolshed[i] === 'band saw'){console.log(mytoolshed[i]);}

  i++;}

console.log('Challenge 3')
