# Experiment No. 6

## 1. Experiment Title

Types of HTML Lists

## 2. Aim

Create unordered, ordered, nested, and description lists.

## 3. Software / Tools Required

- Visual Studio Code or another text editor
- Git and a terminal (for the repository exercises)
- A web browser such as Chrome or Edge (for HTML/CSS exercises)

## 4. Theory

Unordered lists show related items without sequence, ordered lists show sequence, and li marks each entry. Lists may nest to express sub-items. Description lists use dl to group terms and explanations, with dt for each term and dd for its description.

## 5. Algorithm / Procedure

1. Create shopping-list.html with three unordered items: Notebook, Pen, and Bag.

2. Create canteen-menu.html with Samosa and Sandwich; nest Cheese and Vegetable under Sandwich.

3. Create faq.html with the two supplied questions as dt elements and answers in dd elements.

## 6. Program / Queries / Commands

### Task 1 — shopping-list.html

```html
<!-- Name: LOKESH SHUKLA | Roll Number: 2510303281 | Assignment: BCS352 Lab 6 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Shopping List</title>
</head>
<body>
    <h1>Shopping List</h1>

    <ul>
        <li>Notebook</li>
        <li>Pen</li>
        <li>Bag</li>
    </ul>
</body>
</html>
```

### Task 2 — canteen-menu.html

```html
<!-- Name: LOKESH SHUKLA | Roll Number: 2510303281 | Assignment: BCS352 Lab 6 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Canteen Menu</title>
</head>
<body>
    <h1>Canteen Menu</h1>

    <ol>
        <li>Samosa</li>
        <li>Sandwich
            <ol>
                <li>Cheese</li>
                <li>Vegetable</li>
            </ol>
        </li>
    </ol>
</body>
</html>
```

### Task 3 — faq.html

```html
<!-- Name: LOKESH SHUKLA | Roll Number: 2510303281 | Assignment: BCS352 Lab 6 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Frequently Asked Questions</title>
</head>
<body>
    <h1>Library FAQ</h1>

    <dl>
        <dt>How many books can I borrow?</dt>
        <dd>You can borrow books according to the library's borrowing rules.</dd>

        <dt>Is the library open on Sunday?</dt>
        <dd>Please check the library's current opening hours.</dd>
    </dl>
</body>
</html>
```


## 7. Input

### Task 1
Notebook, Pen, Bag.

### Task 2
Samosa, Sandwich, Cheese, Vegetable.

### Task 3
Questions: “How many books can I borrow?” and “Is the library open on Sunday?”; write an answer for each.

## 8. Output

The following images show the output screenshots already present in the GitHub lab folder:

### Task 1

![Task 1 output - Lab 6 - Task 1.png](Lab%206%20-%20Task%201.png)


### Task 2

![Task 2 output - Lab 6 - Task 2.png](Lab%206%20-%20Task%202.png)


### Task 3

![Task 3 output - Lab 6 - Task 3.png](Lab%206%20-%20Task%203.png)


## 9. Result

The pages render a three-item shopping list, a numbered canteen menu with nested choices, and two FAQ terms paired with their answers.

## 10. Viva-Voce Questions

1. When should you use ul instead of ol?
2. Which element represents a list item?
3. What are dt and dd used for?


