# **css**

## **display**

- ### block
- ### inline
- ### inline-block

### **block**

> **display : block**의 경우 지정된 width, height를 제외한 부분이 margin으로 꽉 차게 됩니다.
>
> 다른 요소가 옆으로 올 수 없습니다.

```html
<div style="width:30px; height:30px;background-color:tomato;">1</div>
<div style="width:30px; height:30px;background-color:cornflowerblue;">2</div>
<div style="width:30px; height:30px;background-color:khaki">3</div>
```

### **inline**

> **display : inline**의 경우
> width와 height를 가질 수 없습니다.
>
> contents의 크기로 높이와 너비를 얻습니다.
>
> 다른 요소가 옆으로 올 수 있습니다.

```html
<span style="width:30px; height:30px;background-color:tomato;">1</span>
<span style="width:30px; height:30px;background-color:cornflowerblue;">2</span>
<span style="width:30px; height:30px;background-color:khaki">3</span>
```

### **inline-block**

> **display : inline-block**의 경우 **display : block**과 **display : inline**의 특징이 합쳐있습니다.
>
> **display : block** 처럼 width와 height를 가질 수 있으며
>
> **display : inline** 처럼 다른 요소가 옆에 있을 수 있습니다.

```html
<div
  style="display:inline-block;width:30px; height:30px;background-color:tomato;"
>
  1
</div>
<div
  style="display:inline-block;width:30px; height:30px;background-color:cornflowerblue;"
>
  2
</div>
<div
  style="display:inline-block;width:30px; height:30px;background-color:khaki"
>
  3
</div>
```
