# 🎨 CSS PROPERTIES – STUDY GUIDE (Landing Page Exam)

## 📦 RESET

```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

---

## 🧱 LAYOUT

### Display

```css
display: block;
display: inline;
display: flex;
display: grid;
```

---

### Position

```css
position: static;
position: relative;
position: absolute;
position: fixed;
```

```css
top: 0;
left: 0;
right: 0;
bottom: 0;
z-index: 1;
```

---

## 🧭 FLEXBOX (IMPORTANT)

```css
display: flex;
flex-direction: row;
flex-direction: column;

justify-content: center;
justify-content: space-between;
justify-content: space-around;

align-items: center;
align-items: flex-start;
align-items: flex-end;

gap: 20px;
```

---

## 🧩 GRID

```css
display: grid;

grid-template-columns: repeat(3, 1fr);
grid-template-rows: auto;

gap: 10px;
```

---

## 📐 SIZE

```css
width: 100%;
height: 100vh;
max-width: 1200px;
```

---

## 📦 SPACING

```css
margin: 20px;
margin-top: 10px;
margin-bottom: 10px;

padding: 20px;
padding: 10px 20px;
```

---

## 🎨 COLORS & BACKGROUND

```css
color: white;

background: black;
background: #111;

background: linear-gradient(to right, #ff7b00, #ff3c00);

background: url("image.jpg") center/cover no-repeat;
```

---

## 🔘 BORDER & EFFECTS

```css
border: 1px solid white;

border-radius: 10px;
border-radius: 50%;

box-shadow: 0 5px 15px rgba(0,0,0,0.3);
```

---

## 🧠 TEXT

```css
font-family: Arial, sans-serif;
font-size: 16px;
font-weight: bold;

text-align: center;
text-decoration: none;
```

---

## 🎮 INTERACTION

```css
cursor: pointer;
```

```css
button:hover {
  background: red;
}

.card:hover {
  transform: translateY(-10px);
}
```

---

## 🎞️ TRANSFORM & TRANSITION

```css
transform: scale(1.05);
transform: translateY(-10px);

transition: 0.3s;
```

---

## 🎥 VIDEO BACKGROUND

```css
.video {
  position: absolute;
  width: 100%;
  height: 100%;
}

.overlay {
  position: absolute;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.6);
}
```

---

## 📊 TABLE

```css
table {
  width: 100%;
  border-collapse: collapse;
}

th, td {
  padding: 10px;
  border: 1px solid white;
  text-align: center;
}
```

---

## 📋 LIST

```css
ul {
  list-style: none;
}

li {
  margin-bottom: 10px;
}
```

---

## 📱 RESPONSIVE (VERY IMPORTANT)

```css
@media (max-width: 768px) {

  header {
    flex-direction: column;
  }

  .grid {
    grid-template-columns: 1fr;
  }

  .container {
    flex-direction: column;
  }

}
```

---

## 💥 MOST IMPORTANT COMBO

```css
display: flex;
justify-content: center;
align-items: center;
```

👉 Use this when you don’t know what to do.

---

## 🚀 FINAL TIP

Think like this:

* Navbar → Flex
* Hero → Center with Flex
* Cards → Flex
* Gallery → Grid
* Table → Table structure
* Mobile → Media Query

---
