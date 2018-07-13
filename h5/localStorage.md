### sessionStorage

---

存储数据到本地（存储在当前页面的内存中，生命周期为关闭当前页面），容量5mb左右

`setItem(key,value) 存储数据`

`getItem(key)`

`removeItem(key)`

`clear()`

`window.sessionStorage.setItem(k,v)`

### localStorage

---

* 存储内容20mb
* 不同浏览器不能共享数据，但是在同一个浏览器的不同页面上可以共享数据
* 永久生效，存储在硬盘上，不会随着页面或者浏览器的关闭而清除，只能手动清除



