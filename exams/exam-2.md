# Rounding up the Basics

> ### Exam 2 | 4 questions

### Do you know how to work with all these selectors and combinators?

#### 1. What does the following syntax do?

```css
div .page-title {
    color: red;
```

- :x: It will set a red background color to any element(s)&nbsp;with a class of <code>page-title</code>&nbsp; which are direct children of a <code>&lt;div&gt;</code>&nbsp;&nbsp;element.

- :x: It will set a red text color to any element(s)&nbsp;with a class of&nbsp;<code>page-title</code>&nbsp; which are direct children of a&nbsp;<code>&lt;div&gt;</code>&nbsp;&nbsp;element.

- :white_check_mark: It will set a red text color to any element(s)&nbsp;with a class of&nbsp;<code>page-title</code>&nbsp; which are descendants&nbsp;of a&nbsp;<code>&lt;div&gt;</code>&nbsp;&nbsp;element.

#### 2. What does the following syntax do?

```css
a.active {
  color: white;
}
```

- :white_check_mark: It will set white text color on all `<a href="...">Click me!</a>` elements

- :x: It will set white text color to elements like this:

  ```html
  <a href="..."><span class="active">Click me!</span></a>
  ```

- :x: It will set white text color to elements like this:

  ```html
  <div class="active"><a href="...">Click me!</a></div>
  ```

#### 3. What does the following syntax do?

```css
.active,
a:hover {
  color: white;
}
```

- :x: It'll set a white text color ONLY to elements like this:

  ```html
  <a href="..." class="active">Click me!</a>
  ```

  IF the user is currently hovering over them.

- :white_check_mark: It'll set a white text color ONLY to elements like this:

  ```html
  <a href="..." class="active">Click me!</a>
  ```

  but also to

  ```html
  <a href="...">Click me!</a> IF the user hovers over it.
  ```

#### 4. Why is using !important generally NOT a good idea?

- :white_check_mark: It overwrites the order set by "Specifity" and therefore makes it harder to work with your CSS code.

- :x: It changes the element selected by the rule.

- :x: It's actually fine to use it.
