### transform

---

```
.box {
    transform:rotate3d(1,1,0,-30deg);
    transform-style:preserve-3d;
}
.front {
    transform:translateZ(100px)
}
.back {
    transform:translateZ(100px)
}
.left {
    transform:translateX(-100px) rotateY(90deg)
}
.top {
    transform:translateY(-100px) rotateX()
}
```

perspective :(npx) 设置观察盒子的位置  

perspective-origin：npx npx 