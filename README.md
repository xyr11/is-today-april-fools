# xyr11/is-today-april-fools
Is today April Fools day?

## Installation
If you want an embedded script, download the [`is-today-april-fools.js`](https://github.com/xyr11/is-today-april-fools/blob/main/is-today-april-fools.js) file. For a standalone website version, download the [`index.html`](https://github.com/xyr11/is-today-april-fools/blob/main/index.html) file.

## Usage

### Standalone website verion
Open the HTML file

### Embedded script
`aprFoolsToday()` function
+ Returns `true` if today is April Fools Day and `false` if it isn't

Sample code:
```html
<script src="is-today-april-fools.js"></script>
<script>
  if (aprFoolsToday()) {
    console.log("Today is April Fools Day! 😀");
  } else {
    console.log("Today is *definitely* not April Fools Day 😔");
  }
</script>
```
### On the web
Visit <https://xyr11.github.io/is-today-april-fools/>

## License
This project is licensed under [MIT License](https://github.com/xyr11/is-today-april-fools/blob/main/LICENSE)

<br>
<details>
  <summary></summary>

  ## Known Issues
  Returns `false` on April Fools Day because Happy April Fools! Yeah, the function just returns `false` every time nonetheless. If you didn't see it coming, this repo is a joke 😉
</details>
