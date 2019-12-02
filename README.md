# `What I Learned In Week 13`

### `.forEach Method`

* Instead of looping for each index, we can use this method which is shorter and easier.
  
* instead of this: 
``` javascript
const forEach = function(arr, callback) {
    for (let i = 0; i<arr.length; i++){
        callback(arr[i]);
    }
}
```
* We can use this: 
``` javascript
students.forEach(function(student){
    console.log(student)
})
```
