## ES6 Part-2

```
// problem-1
const oddNumbers = [1, 3, 5, 7, 9];

const even = oddNumbers.map((e) => e + 1);
// console.log(even);

// problem-2
const array = [33, 50, 79, 78, 90, 101, 30];
const result = array.filter((num) => num % 10 === 0);
const result2 = array.find((num) => num % 10 === 0);
// console.log(result2);

// problem-3
const instructor = [
  { name: "Nodi", age: 28, position: "senior" },
  { name: "Akhil", age: 26, position: "junior" },
  { name: "Sobuj", age: 30, position: "senior" },
];
const senior = instructor
  .filter((sen) => sen.position === "senior")
  .map((sen) => sen.name);

// console.log(senior);

// problem-4
const people = [
  { name: "meena", age: 20 },
  { name: "Rina", age: 15 },
  { name: "Sushorita", age: 22 },
];
const output = people.reduce((p, c) => p + c.age, 0);
console.log(output);

```
