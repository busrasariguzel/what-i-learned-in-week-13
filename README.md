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
### `Arrow Function`
``` javascript
const Jstudents = students.filter((student) => student.startsWith('J'))
```

----

 ### `Linkled list`

```javascript
const LinkedList = {
head : {
    value :3,
    next : {
        value :15,
        next :{

        }
    }
}
}

const node1 = {
    value :3,
    next:node2
}

const node2 = {
    value :15,
    next:null
}

console.log(linkedList.head.next.value) ==== 3



```
* Accessing a index or finding an index is very inefficient.
* adding or removing easy
* adding is important and efficient
* but finding a specific data is not -- so use array instead of linked list.
* algorithm 


