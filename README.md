# isType
# 实现原理： * 通过函数上的原型下的toString方法将this指向形参
  function isType(obj) {              
      // Object.prototype.toString.call(obj)打印[Object 值类型]              
      return Object.prototype.toString.call(obj).slice(8,-1)          
  }          
  isType(实参)
