# JavaScript output

Ways to display data in JavaScript:

+ Writing into an alert box, using `window.alert()`

```html

<!DOCTYPE html>
<html>
    <body>

        <h1>This is a header</h1>
        <p>This is a paragraph</p>

        <script>
            window.alert(2 + 2);
        </script>

    </body>
</html>

```
----

+ Writing into the HTML output using `document.write()`

```html

<!DOCTYPE html>
<html>
    <body>

        <h1>This is a header</h1>
        <p>This is a paragraph</p>

        <script>
            document.write(2 + 2);
        </script>

    </body>
</html>

```

Another example using an `onclick event`:

```html

<!DOCTYPE html>
<html>
    <body>

        <h1>This is a header</h1>
        <p>This is a paragraph</p>

        <button onclick="document.write(2 + 2)">Click me!</button>

    </body>
</html>

```
----


+ Writing into an HTML element, using `innerHTML`

```html

<!DOCTYPE html>
<html>
    <body>

        <h1>This is a header</h1>
        <p>This is a paragraph</p>

        <p id="test"></p>

        <script>
            document.getElementById("test").innerHTML = 2 + 2;
        </script>

    </body>
</html>

```
---

+ Writing into the browser console, using `console.log()`

```html
<!DOCTYPE html>
<html>
    <body>

        <h1>This is a header</h1>
        <p>This is a paragraph</p>

        <script>
            console.log(2 + 2);
        </script>

    </body>
</html>

```

### Next...
Go [back](https://github.com/MyPitit/JavaScript-Tutorial) or to the [next](https://github.com/MyPitit/JavaScript-Tutorial/blob/master/syntax.md) lesson.
