# cssFragment
css code snippet 我的css代码片段

### ios中输入框边缘有阴影
ios中输入框边缘有阴影，无法用box-shadow:none清除，可以用下面方法清除掉
```
input{
      -webkit-appearance: none;
              appearance: none;
}
```

### ios中给body加user-select: none;会导致输入框无法被选中
ios中给body加user-select: none;会导致输入框无法被选中，从而无法输入。可以给input加user-select: all;
```
input{
            user-select: all;
    -webkit-user-select: all;
}
```
