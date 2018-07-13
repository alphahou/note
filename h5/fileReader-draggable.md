#### FileReader

---

```
const reader=new FileReader()
const file=document.querySelector('[type='file']').files
reader.readAsDataURL(file[0])

//onload 读取成功时触发，onloadend 读取完成时触发

reader.onload=()=>document.querySelector('img').src=reader.result
```





#### Draggable

---

##### 应用于被拖拽元素的方法

ondrag ondragstart ondragleave ondragend



##### 应用于目标元素的方法

ondragenter ondragover（停留在目标元素上时调用） ondrop ondragleave

在ondragover方法上阻止默认事件