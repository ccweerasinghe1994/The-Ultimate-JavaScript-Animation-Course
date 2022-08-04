# JS ANIMATIONS

## javascript animations

```css
* {
  margin: 0;
  padding: 0;
}
section {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}

button {
  background-color: rgb(30, 30, 30);
  color: white;
  padding: 1rem 2rem;
  border: none;
  font-size: 1.5rem;
  transition: background 0.75s ease-out;
}
button:hover {
  background-color: rgb(42, 65, 115);
}

nav {
  min-height: 10vh;
  background-color: rgb(30, 30, 30);
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  transition: transform 0.75s ease-out;
}

.nav-slide {
  transform: translateY(-100%);
}

p {
  font-size: 1.5rem;
  opacity: 0;
  transition: opacity 0.75s ease-out 0.5s;
}
.fade {
  opacity: 1;
}
```
