# CSS Foundation

## Basic Syntax
```
        dir.bold-text{
            font-weight: 100;
        }
```
Here, `dir.bold-text` is **selector**, `font-weight` is **property** and `100` is **value**.
Selector refers to HTML elements to which CSS rule apply.

<hr>

## Types of Selectors

1. Universal Selector
2. Type Selector
3. Class Selector
4. Id Selector
5. Grouping Selector
6. Chaining Selector
7. Descendant Combinator

<br>

### Universal Selector:
* Syntax: 
    ``` 
        * {
            color: purple;
        }
    ```
* It will select  all elements irrespective of their type.


### Type Selector: 
* Syntax:
    ```
        div {
              color: white;
        }
    ```
* It will select all elements of given element.

### Class Selector:
* Syntax:
    ```
        .alert-text {
            color: red;
        }
    ```
* It will select all element with a given class.
* class name would be prefixed by `(.)`.

### ID Selector:
* Syntax:
    ```
        #title-name {
            background-color: red;
        }
    ```
* It will select element with given ID.
* An element can have only one ID.
* An ID can not be repeated on a single page.

### Grouping Selector:
* Syntax:
    ```
        .read, .unread {     <!-- two classes combined using (,) -->
            color: white;
            background-color: black;
        }

        .read {
            ----
            .read separate properties
            ---- 
        }

### Chaining Selector:
* Syntax:
    ```
        .subsection.header {  <!-- chained by using no spacing between two class names -->
            color: red;
        }
    ```
* It will select an element that has both classes.
* No spacing between two classes name.
* Also works with Class-Id pair and vice versa, Element-Class pair, Element-ID pair.

### Descendant Selector:
* Syntax:
    ```
        <div class="x">
            <div class="y">
            <div class="y">
            </div>
            </div>
        </div>

        <div class="y"> ----- </div>
    ```
    ```
        .x .y { <!-- descendant selected by providing space ( ) between two class name -->
            color: red;
        }
    ```
* In above syntax, it will only select above two element with `class="y"`.
* It is applied in CSS by a single space between selectors.
* It will only cause elements that match the last selector to be selected if they have an ancestor that matches the previous selector.

<hr>

## CSS Properties: