# 🎨 Interactive Shape Drawer

An interactive **JavaScript + HTML Canvas** project that dynamically draws **20+ mathematical and artistic shapes** such as the Butterfly curve, Heart, Cardioid, Spirals, Rose curves, and more.  
Users can select a shape from a **dropdown menu**, and it will start animating in real-time.  

---

## ✨ Features
- 🖌️ **20+ unique shapes** (Butterfly, Heart, Spiral, Cardioid, Rose, Lissajous, Hypotrochoid, etc.)  
- 🎞️ **Animated drawing** for smooth visualization  
- 📂 **Dropdown menu** for shape selection  
- 🏷️ Shape name displayed under the drawing  
- 📱 **Responsive canvas** (adjusts to screen size)  
- 🧩 Easy to extend: add your own shapes!  

---

## 📸 Preview
*<img width="1238" height="910" alt="image" src="https://github.com/user-attachments/assets/2d2867f1-66ba-46b8-bd35-af5d905ca3cf" />*  

---

## 📐 Shapes Included
1. Butterfly Curve 🦋  
2. Circle ⭕  
3. Heart ♥  
4. Spiral 🌀  
5. Lissajous Curve  
6. Rose Curve 🌹  
7. Lemniscate of Bernoulli (∞)  
8. Cardioid  
9. Star ✨  
10. Ellipse  
11. Hypotrochoid (Spirograph)  
12. Epitrochoid  
13. Astroid  
14. Nephroid  
15. Folium Curve  
16. Cloverleaf ☘️  
17. Figure-8 Curve  
18. Deltoid Curve  
19. Teardrop Shape 💧  
20. Polygon Approximation 🔺  

---

## 🛠️ Technologies Used
- **HTML5** – Structure  
- **CSS3** – Styling  
- **JavaScript (Canvas API)** – Shape rendering & animations  

---

## 📂 Project Setup
1. Clone or download the project folder  
2. Open the `index.html` file in any modern browser  
3. Use the **dropdown menu** to select a shape  
4. Watch the curve animate in real-time ✨  

---

## ⚡ Usage
- Great for **learning parametric equations** & **visualizing math**  
- Can be used as a **creative animation project** or **portfolio showcase**  
- Extendable: add your own shapes in the `shapes` dictionary  

---

## 📌 Example Code (Adding New Shape)
```js
shapes.myShape = (θ) => {
  const r = 200 * Math.cos(3*θ);
  return { x: r * Math.cos(θ), y: r * Math.sin(θ) };
};
