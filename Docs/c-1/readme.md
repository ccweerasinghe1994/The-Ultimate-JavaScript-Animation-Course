# JS ANIMATIONS

- [JS ANIMATIONS](#js-animations)
  - [CSS animations](#css-animations)

## CSS animations

let's add the home page.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
  </head>
  <body>
    <section>
      <button>Hover Me</button>
    </section>
  </body>
</html>
```

and the css

```css
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
```

output
![image](../img/1.png)
