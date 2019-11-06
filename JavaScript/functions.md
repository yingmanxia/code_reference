# JavaScript
#### 判断对象类型
* curry将一个函数拆分成多个函数
* Object.prototype.toString.call
```javascript
const checkType=(content,type)=>{
    return Object.prototype.toString.call(content) === `[object ${type}]`
}
const b = checkType(123,'Number')
```
