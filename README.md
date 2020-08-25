# china-website-icon

* 角标位置：支持左上、左下、右上、右下、底部居中、自定义。
* 角标形状：标准、圆形、正方形、地图。

---

### 使用方式

* 默认：`<script src="https://cdn.jsdelivr.net/gh/gokins/china-website-icon/src/i-love-china.js"></script> `
* 左下：`<script src="https://cdn.jsdelivr.net/gh/gokins/china-website-icon/src/i-love-china.js" layout="left-bottom"></script> `
* 左下正方形：`<script src="https://cdn.jsdelivr.net/gh/gokins/china-website-icon/src/i-love-china.js" style="square" layout="left-bottom"></script> `
* 底部居中地图：`<script src="https://cdn.jsdelivr.net/gh/gokins/china-website-icon/src/i-love-china.js" style="map" layout="bottom-center" width="32px" height="32px"></script> `
* 一直显示在窗口：`<script src="https://cdn.jsdelivr.net/gh/gokins/china-website-icon/src/i-love-china.js" position=""></script> `

参数说明：

`<script src="https://staticqn.gitkin.com/i-love-china.js" style="形状" layout="位置" width="宽度" height="高度" left="距左" right="距右" top="距顶" bottom="距下" position="浮动方式"></script> `

* style ： oblong（长方形），square（正方形），circle（圆形），map（地图）
* layout：right-top（右上）、left-top（左上）、left-bottom（左下）、right-bottom（右下）、bottom-center（底部居中）、custom（自定义）。
* width/height/left/right/top/bottom：可以是px也可是%，如32px、10%。
* position：absolute（绝对定位）、fixed（相对窗口定位）、relative（正常定位）
