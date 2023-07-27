# Are you a Flexbox expert already?

> ### Exam 4 | 4 questions

#### 1: What is the purpose of Flexbox and why should we use it to our project?

- :x: With Flexbox we can easily create responsive websites which look good on mobile and desktop device.

- :white_check_mark: Flexbox allows us to dynamically change and define the behaviour of elements inside a so-called flex-container.

- :x: Flexbox helps us to easily change the size of the elements on a website.

#### 2: The main axis always goes from the left to the right, whereas the cross axis always goes from the top to the bottom of our website.

- :x: This is correct.

- :x: No, that's not correct. The main axis can also start on the right and go to the left, the cross axis can start at the bottom and go to the top too.

- :white_check_mark: No that's not correct. Main axis and cross axis can change its position as the main axis is defined by the `flex-direction` property. For `row` the main axis goes from left to right (or right to left for `row-reverse`) and for `flex-direction: column` the main axis goes from top to bottom (or bottom to top for `column-reverse` ).

#### 3: How can I center all elements inside the flex-container both vertically and horizontally?

- :x: This can be achieved by adding `justify-content: center` to center the items horizontally and `align-items: center` to center the items along the vertical axis.

- :white_check_mark: This can be achieved by adding `justify-content: center` to center the items along the main axis and `align-items: center` to center the items along the cross axis.

- :x: This is not possible with Flexbox as we can only specify the wrapping behaviour of the elements inside the flex-container.

#### 4: What are the default properties and corresponding values automatically set after applying `display: flex` to an element?

- :x: No properties are set automatically. Using `display: flex` will turn the element it is applied to into a flex-container, the behaviour has to be specified manually afterwards.

- :x: Adding `display: flex` will turn the element into a flex-container with `flex-direction: row` and `flex-wrap: wrap` being automatically applied.

- :white_check_mark: Adding `display: flex` will turn the element into a flex-container with the `flex-direction: row` and `flex-wrap: no-wrap` declarations being automatically applied.
