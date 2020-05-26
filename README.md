# Swip
#### 原库位置

[开源地址](https://github.com/nolimits4web/swiper "开源地址")

#### 导入核心库
```html
<!-- 导入别人写好的库 -->
<link rel="stylesheet" href="swiper.min.css">
<script src="swiper.min.js"></script>
```

#### 基本使用

### 1
```html
<div class="swiper-container">
	<div class="swiper-wrapper">
		<div class="swiper-slide">内容1</div>
		<div class="swiper-slide">内容2</div>
	</div>
</div>
```

### 2
```css
.swiper-container {
	width: 100%;
	height: 660px;
}

.swiper-slide {
	text-align: center;
	font-size: 180px;
	background: #fff;
	color: white;
	/* Center slide text vertically */
	display: -webkit-box;
	display: -ms-flexbox;
	display: -webkit-flex;
	display: flex;
	-webkit-box-pack: center;
	-ms-flex-pack: center;
	-webkit-justify-content: center;
	justify-content: center;
	-webkit-box-align: center;
	-ms-flex-align: center;
	-webkit-align-items: center;
	align-items: center;
}
```

### 3
```javascript
//页面加载后执行
window.onload = function() {
	var mySwiper = new Swiper('.swiper-container', {
		//direction: 'vertical', // 垂直切换选项
		loop: true, // 循环模式选项
		autoplay: {
			delay: 2000, //自动轮播时间
			disableOnInteraction: false //用户操作后不轮播
		}
	})
}
```

#### 常用API
##暂时无

