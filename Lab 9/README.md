# Experiment No. 9

## 1. Experiment Title

Tables with Headers and Footers

## 2. Aim

Structure tabular data with a caption, header, body, footer, and scope attributes.

## 3. Software / Tools Required

- Visual Studio Code or another text editor
- Git and a terminal (for the repository exercises)
- A web browser such as Chrome or Edge (for HTML/CSS exercises)

## 4. Theory

Tables present data in rows and columns. Caption names the table, thead groups headings, tbody groups records, and tfoot contains a summary. th identifies a header and td a data cell. Scope clarifies whether a header applies to a column or row, improving accessible navigation.

## 5. Algorithm / Procedure

1. Create marks.html with caption, Name/Maths/Science headings, and the three specified student rows.

2. Create marks-average.html with Asha and Rohan and a footer containing the class averages.

3. Create marks-accessible.html with Asha and Rohan and scope=col / scope=row on the appropriate header cells.

## 6. Program / Queries / Commands

### Task 1 — marks.html

```html
<!-- Name: LOKESH SHUKLA | Roll No: 2510303281 | Assignment: BCS352 Lab 9 -->

<!DOCTYPE html>
<html>
<head>
    <title>Class Marks</title>
</head>
<body>

    <table border="1">
        <caption>Marks of Class A</caption>

        <thead>
            <tr>
                <th>Name</th>
                <th>Maths</th>
                <th>Science</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>Asha</td>
                <td>78</td>
                <td>85</td>
            </tr>
            <tr>
                <td>Rohan</td>
                <td>64</td>
                <td>70</td>
            </tr>
            <tr>
                <td>Neha</td>
                <td>91</td>
                <td>88</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
```

### Task 2 — marks-average.html

```html
<!-- Name: LOKESH SHUKLA | Roll No: 2510303281 | Assignment: BCS352 Lab 9 -->

<!DOCTYPE html>
<html>
<head>
    <title>Class Marks Average</title>
</head>
<body>

    <table border="1">
        <caption>Marks of Class A</caption>

        <thead>
            <tr>
                <th>Name</th>
                <th>Maths</th>
                <th>Science</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <td>Asha</td>
                <td>78</td>
                <td>85</td>
            </tr>
            <tr>
                <td>Rohan</td>
                <td>64</td>
                <td>70</td>
            </tr>
        </tbody>

        <tfoot>
            <tr>
                <th>Class average</th>
                <td>71</td>
                <td>77.5</td>
            </tr>
        </tfoot>
    </table>

</body>
</html>
```

### Task 3 — marks-accessible.html

```html
<!-- Name: LOKESH SHUKLA | Roll No: 2510303281 | Assignment: BCS352 Lab 9 -->

<!DOCTYPE html>
<html>
<head>
    <title>Accessible Marks Table</title>
</head>
<body>

    <table border="1">
        <caption>Marks of Class A</caption>

        <thead>
            <tr>
                <th scope="col">Name</th>
                <th scope="col">Maths</th>
                <th scope="col">Science</th>
            </tr>
        </thead>

        <tbody>
            <tr>
                <th scope="row">Asha</th>
                <td>78</td>
                <td>85</td>
            </tr>
            <tr>
                <th scope="row">Rohan</th>
                <td>64</td>
                <td>70</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
```


## 7. Input

### Task 1
Asha 78/85; Rohan 64/70; Neha 91/88.

### Task 2
Asha and Rohan marks; calculate the average for each subject.

### Task 3
Asha and Rohan data with column and row scope attributes.

## 8. Output

The following images show the output screenshots already present in the GitHub lab folder:

### Task 1

![Task 1 output - Lab 9 - Task 1.png](Lab%209%20-%20Task%201.png)


### Task 2

![Task 2 output - Lab 9 - Task 2.png](Lab%209%20-%20Task%202.png)


### Task 3

![Task 3 output - Lab 9 - Task 3.png](Lab%209%20-%20Task%203.png)


## 9. Result

The pages render the class marks table, a two-student average row (Maths 71; Science 77.5), and an accessible table with row and column scope attributes.

## 10. Viva-Voce Questions

1. What are thead, tbody, and tfoot used for?
2. How do th and td differ?
3. What does the scope attribute communicate?



