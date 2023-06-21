# Selectors & Combinators

> ### Exam 1 | 5 questions

### Do you know how to work with all these selectors and combinators?

#### 1. What's a "Rule" in CSS?

- :x: The instruction HOW to style a given property.

- :white_check_mark: A combination of selector ("WHAT to style") and declaration ("HOW to style it").

- :x: The import statement which points at an external CSS file.

#### 2. Which selector would select this element?

```html
<h1 class="page-title">Dive into the core features</h1>
```

- :x: `#page-title { ... }`

- :x: `page-title { ... }`

- :x: `[page-title] { ... }`

- :white_check_mark: `.page-title { ... }`

#### 3. What is "Specificity" about?

- :x: Specificity is a CSS best practice which instructs you that you target an element with the most specific selector possible.

- :x: Specificity describes the fact that multiple CSS rules can target the same element.

- :white_check_mark: Specificity is all about resolving conflicts that arise from multiple CSS rules which target the same element.

#### 4. What's a Combinator?

- :white_check_mark: A CSS feature which allows you to combine two selectors in a dependent way.

- :x: A CSS feature which allows you to combine two selectors in an independent way.

- :x: A CSS feature which allows you to group a CSS rule by selectors.

#### 5. Why should you NOT use inline styles (`<div style="...">` )?

- :x: Because it has the lowest specifity.

- :x: Because they are only available on some HTML elements.

- :white_check_mark: Because the code becomes harder to maintain and predict.
