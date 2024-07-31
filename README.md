//task1

// function test(array, grade) {
//     for (let keys in array) {
//         if (grade == array[keys].grade) {
//             return array[keys]
//         }
//     }
// }
// console.log(test([{ name: "Alice", grade: "B" }, { name: "Bob",grade: "A" }, { name: "Charlie", grade: "C" }, ] ,"A"));

//task2

// function test(array,a,b) {
//     let result = 0
//     for (let keys in array) {
//         if (a <= array[keys].price && b == array[keys].category) {
//           result =   array[keys]
//         }
//     }
//     return result
// }
// console.log(test([ 
{ name: "Laptop", price: 800, category:
// "электроника" }, { name: "Headphones", price: 30, category:
// "электроника" }, { name: "Book", price: 15, category: "книги" } ],
// 520, "электроника"))

//task10

// function test(object) {
//     let cnt=0
//     for(let keys in object) {
//         cnt+=object[keys]
//     }
//     return cnt>=50
// }
// console.log(test({ "Shampoo": 5.99, "Rubber Ducks": 15.99 }));



// function test(arr, key){
//     let result = {}
//     for(let obj of arr){
//         result[obj[key]] = obj
//     }
//     return result
// }
// console.log(test([{id: 1, name: "Alice"},{id: 2, name: "Bob"},{id: 3, name: "Charlie"},],"id"));




// Task7
// function test(keys, values){
//     let obj = {}
//     keys.forEach((key, index)=>{
//         obj[key] = values[index]
//     })
//     return obj
// }
// console.log(test(["name", "age", "city"], ["Alice", 25, "NewYork"]));

// Task8
// function test(arr, key){
//     let maxObject = null;
//     let maxValue = Number.NEGATIVE_INFINITY;
//     for(let obj of arr){
//         if(obj[key] > maxValue){
//             maxObject = obj
//             maxValue = obj[key]
//         }
//     }
//     return maxObject
// }
// console.log(test([{name: "Alice", age: 25},{name: "Bob",age:30},{name: "Charlie", age: 22},],"age"));

// function test(a, b, c){
//     let ans = []
//     for(let i=0; i<a.length; i++){
//         if(a[i].price >= b && a[i].category == c){
//             ans.push(a[i])
//         }
//     }
//     return ans
// }
// console.log(test([{name: "Laptop", price: 800, category: "электроника" },{name: "Headphones", price: 30, category:"электроника" },{name: "Book", price: 15, category: "книги" }],50, "электроника"));
