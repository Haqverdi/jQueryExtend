# jQueryExtend
Pure Javascript version of Jquery $.extend function for use in older browsers, where es6 or newer features are not supported e.g. spread operator (ES2018) :)

## Usage

1. Download `extend.min.js`
2. Add to end of file where, will be use object combine
3. 
```
let first = {
	first: 1
}
let second = {
	second: 2
}
let others = {
	third: 3,
	fourth: 4,
	fifth: 5
}
const new_obj = extend(first, second, others);
console.log(new_obj); // { first: 1, second: 2, third: 3, fourth: 4, fifth: 5 }
```
