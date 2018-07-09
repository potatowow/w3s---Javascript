### w3s - JS Introduction
#### Javascript 可以改變HTML內容(content)
```js
document.getElementById('demo').innerHTML = 'Hello Javascript';
```
- 使用方法找到HTML元素並修改元素的內容(innerHTML)
- '單引號'符號也可以用"雙引號"

#### Javascript 可以改變HTML屬性質(Attribute Values)
```js
<button onclick="document.getElementById('myImage').src='pic_bulboff.gif'">Turn off the light</button>
```

#### Javascript 可以改變HTML樣式(CSS)

```js
document.getElementById('demo').style.fontSize = '35px';
```

#### Javascript 可以隱藏HTML元素
可以透過改變disaplay樣式隱藏HTML元素
```js
document.getElementById('demo').style.display = 'none';
```

#### Javascript 可以顯示HTML元素
透過改變disaplay樣式顯示HTML元素
```js
document.getElementById('demo').style.display = 'block';
```
