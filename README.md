# Examples on how to use this package

```
const dsa = require('firstdsapackage');

const arr=[5,3,4,2,1];

const pq=new dsa.DataStructers.PriorityQueue((a,b)=>a>b);
pq.insert(10);
pq.insert(20);
pq.insert(30);
pq.insert(40);
pq.insert(50);
pq.display();

dsa.Algorithms.QuickSort(arr);
console.log(arr);

```