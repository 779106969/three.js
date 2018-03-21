# three.js #
## 一.步骤 ##
### 1.引入js文件 ###
```html
//作用：Three.js库
<script src="js/three.js"></script>

//作用：检测当前浏览器是否支持或者开启了WEBGL
<script src="js/Detector.js">/script>

//作用：监控代码的性能
<script src="js/Stats.js">/script>

//作用：控制鼠标旋转缩放
<script src="js/OrbitControls.js">/script>
```
### 2.建立场景 ###
```javascript
let scene = new THREE.Scene();
```
### 3.添加摄像头 ###
```javascript
let camera = new THREE.PerspectiveCamera( 70, window.innerWidth / window.innerHeight, 0.1, 1000 );
```
### 4.添加渲染器 ###
```javascript
var renderer = new THREE.WebGLRenderer();
```
### 5.鼠标控制旋转 ###
```javascript
let controls = new THREE.OrbitControls( camera, renderer.domElement );
```
### 6.绘制三维坐标 ###
### 7.数据处理 ###





