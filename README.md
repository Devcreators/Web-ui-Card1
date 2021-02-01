# 참고 강의
> [OnlineTutorials](https://ibit.ly/OKNt)

# 실행 결과
<img src="https://user-images.githubusercontent.com/58944350/106442472-a7665f00-64be-11eb-86d1-89ac23a7a87d.PNG" width="800" height="260">

``` css
/* 공통 코드 */
* {
  margin: 0;
  padding: 0;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-width: 100vh;
  background: #26ed93;
}

.container {
  position: relative;
  display: flex;
  flex-direction: row;
}

.container .box {
  position: relative;
  width: 200px;
  height: 200px;
  margin: 350px 10px;
  background: #fff;
  font-family: cursive;
  font-size: 2.5em;
  display: flex;
  justify-content: center;
  align-items: center;
  color: rgba(0, 0, 0, 0.4);
}
```

---

### Card01
<img src="https://user-images.githubusercontent.com/58944350/106442474-a7fef580-64be-11eb-8df7-6dd9e918ed37.PNG" width="400" height="260">

```css
.container .box.shadow1 {
  box-shadow: -30px 30px 20px rgba(0, 0, 0, 0.3);
  border-radius: 15px;
}
```

---

### Card02
<img src="https://user-images.githubusercontent.com/58944350/106442476-a8978c00-64be-11eb-931b-0fe30d739e31.PNG" width="400" height="260">

```css
.container .box.shadow2 {
  border-radius: 15px;
}
.container .box.shadow2::before {
  content: '';
  position: absolute;
  bottom: 10px;
  left: 10%;
  width: 90%;
  height: 50px;
  background: rgba(0, 0, 0, 0.3);
  transform-origin: left;
  transform: skewY(5deg);
  z-index: -1;
  filter: blur(5px);
}
```

---

### Card03
<img src="https://user-images.githubusercontent.com/58944350/106442477-a8978c00-64be-11eb-8ce7-f02c1cdefd32.PNG" width="400" height="260">

```css
.container .box.shadow3 {
  border-radius: 15px;
}
.container .box.shadow3::before {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 50%;
  height: 30px;
  background: rgba(0, 0, 0, 0.3);
  transform-origin: right;
  transform: skewY(-8deg);
  z-index: -1;
  filter: blur(10px);
}
.container .box.shadow3::after {
  content: '';
  position: absolute;
  bottom: 0;
  right: 0;
  width: 50%;
  height: 30px;
  background: rgba(0, 0, 0, 0.3);
  transform-origin: left;
  transform: skewY(8deg);
  z-index: -1;
  filter: blur(10px);
}
```

---

### Card04
<img src="https://user-images.githubusercontent.com/58944350/106442478-a9302280-64be-11eb-995e-594e615b04a6.PNG" width="400" height="260">

```css
.container .box.shadow4 {
  border-radius: 15px;
}
.container .box.shadow4::before {
  content: '';
  position: absolute;
  bottom: -50px;
  left: 5%;
  width: 90%;
  height: 20px;
  background: rgba(0, 0, 0, 0.3);
  border-radius: 50%;
  z-index: -1;
  filter: blur(10px);
}
```

---

### Card05
<img src="https://user-images.githubusercontent.com/58944350/106457788-d2f34480-64d2-11eb-9c76-a3a82a9cd423.PNG" width="400" height="260">

```css
.container .box.shadow5 {
  border-radius: 15px;
}
.container .box.shadow5::before {
  content: '';
  position: absolute;
  bottom: -15%;
  left: 5%;
  width: 90%;
  height: 90%;
  background: rgba(0, 0, 0, 0.3);
  z-index: -1;
  filter: blur(10px);
}
```

---

### Card06
<img src="https://user-images.githubusercontent.com/58944350/106442481-a9c8b900-64be-11eb-9e3d-a8ad4285a63f.PNG" width="400" height="260">

```css
.container .box.shadow6 {
  background: #26ed93;
  border-radius: 15px;
  box-shadow: -15px -15px 15px rgba(255, 255, 255, 0.2),
    15px 15px 15px rgba(0, 0, 0, 0.1);
}
```

---

### Card07
<img src="https://user-images.githubusercontent.com/58944350/106442483-aa614f80-64be-11eb-945b-cb6abeb7f399.PNG" width="400" height="260">

```css
.container .box.shadow7 {
  background: #26ed93;
  border-radius: 15px;
  box-shadow: -15px -15px 15px rgba(255, 255, 255, 0.2),
    15px 15px 15px rgba(0, 0, 0, 0.1),
    inset -5px -5px 5px rgba(255, 255, 255, 0.2),
    inset 5px 5px 5px rgba(0, 0, 0, 0.1);
}

```

---

## 작성일자 : 2021-02-01
