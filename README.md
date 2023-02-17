# Intersections-and-differences-in-sets

var set1 = new Set([1, 2, 3, 4]),
 set2 = new Set([3, 4, 5, 6]);
const intersection = new Set(Array.from(set1).filter(x => set2.has(x)));//Set {3, 4}
const difference = new Set(Array.from(set1).filter(x => !set2.has(x))); //Set {1, 2}
