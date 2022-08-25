# Homework

## exercise 1 (example) Access index 0 from the following data structure:

```javascript

const example = [1,2,3,4,5]

// answer: 1 
// explanation: you console.log(example[0]) to get that result.
```
## exercise 2 (example) Access 'human' key from the following data structure:

```javascript

const example = {'human': true, 'animal': false}

// answer: true
// explanation: you console.log(example['human']) to get that result.

```
## exercise 3 (example) Access index 1 and then the key 'human'
```javascript

const example = ['sugar', {'human': true, 'animal': false}, 'test', 'hello']

// answer: true
// explanation: you console.log(example[0]['human'] ) to get that result.

```
## exercise 4 What do you need to do to get 'strong' as a value when printing to the console?

```javascript

const animals = [
    {snake: 'weak', size: 'large', intelligence: 3},
    {monkey: 'strong', size: 'medium', intelligence: 7},
    {human: 'weak', size: 'medium', intelligence: 10}
]

```

## exercise 5 You need to access the key 'sugar'

```javascript

const items = [true, false, 1, 3, 5, {
    subItems: [false, {
        sugar: true
    }, false]
}]

```

## exercise 6 You need to access the key 'difficult'

```javascript

const items = [true, false, 1, 3, 5, {
    subItems: [false, {
        sugar: true, subSubItems: [true, true,
            {difficult: true}
        ]
    }, false]
}]

```

## exercise 7 Do an iteration and ADD all of the values (example [1,2,3] = 6, example2 [5,5,5] = 15)

```javascript

const arr = [1,2,4,7,9,1,3];

//hint: you need a variable with 'let' and not 'const' starting at 0. For every iteration you add the current value in the iteration with what you have in that variable, eventually you will get the sum of all values.

```

## exercise 8 Do an iteration and ADD ONLY index 0 to index 4, ignore all of the other indexes

```javascript

const arr = [4,2,4,7,9,1,3,9,7000];

```

## exercise 9 Do an iteration and ADD ONLY those numbers that are DIFFERENT to 4

```javascript

const arr = [4,4,4,7,2,2,3,10,7000, 4, 4];

```
## exercise 10 Do an iteration and ADD ONLY those numbers that are DIFFERENT to 4

```javascript

const arr = [4,4,4,7,2,2,3,10,7000, 4, 4];

```

## exercise 11 Do an iteration and ADD ONLY those number with key 'valid' as true. Ignore those are not valid.

```javascript

const arr = [
    {valid: true, num: 70},
    {valid: true, num: 10},
    {valid: false, num: 10.7},
    {valid: true, num: 40},
    {valid: false, num: 7.7},
    {valid: false, num: 8.5},
];

// hint: you need a conditional to check if it is valid or not, then just add the key num to a variable that you will create to store the total.
```

## exercise 11 Do an iteration and ADD ONLY those number with key 'valid' as true and key 'color' as blue

```javascript

const arr = [
    {valid: true, num: 70, color: "blue"},
    {valid: true, num: 10, color: "red"},
    {valid: false, num: 10.7, color: "red"},
    {valid: true, num: 40, color: "blue"},
    {valid: false, num: 7.7, color: "red"},
    {valid: false, num: 8.5, color: "blue"},
];

```