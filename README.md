# js-cheat
js cheat sheet

const firstDupeIndex = list => list.findIndex((item, index) => list.lastIndexOf(item) !== index);

find the index of the first duplicate in an array.

const sum = [1, 2, 3].reduce((partial_sum, a) => partial_sum + a); 

Sum all array values

const fact = (n) => n === 0 ? 1 : n * fact(n - 1);

find facotrial of a number
