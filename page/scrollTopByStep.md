# “PAGE” 方法

## $t.scrollTopByStep(step, ?target)

使 target 目标元素内部的滚动条向上滚动 step 距离

## 参数

<i style="color: #3492ff;font-weight: 700;">step (number)</i>: 每次滚动的距离。

<i style="color: #3492ff;font-weight: 700;">target (Element)</i>:  目标元素。默认为 `window`。

## 示例

```javascript
$t.scrollTopByStep(20) // 整个页面的滚动条向上滚动 20 像素

$t.scrollTopByStep(20, document.getElementById('box')) // id="box" 的元素内部的滚动条向上滚动 20 像素
```
