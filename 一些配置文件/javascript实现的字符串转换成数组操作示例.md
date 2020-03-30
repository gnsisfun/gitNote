字符串转换成数组
JavaScript

var str="abcdefg"
 //1、将字符串转成数组形式：split()
 var arr=str.split("")
 console.log(arr)//["a", "b", "c", "d", "e", "f", "g"]
 //2、将数组转成字符串形式：join()
 var strings=arr.join("")//
 console.log(strings)//abcdefg
 //2、将数组元素反转：reverse()函数只能反转数组
 var rever=arr.reverse()
 console.log(rever.join(""))//gfedcba