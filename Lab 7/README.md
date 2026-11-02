# Experiment No. 7

## 1. Experiment Title

About Me Page

## 2. Aim

Build a simple personal page using semantic page regions, an about section, and an email link.

## 3. Software / Tools Required

- Visual Studio Code or another text editor
- Git and a terminal (for the repository exercises)
- A web browser such as Chrome or Edge (for HTML/CSS exercises)

## 4. Theory

Semantic elements explain the role of page regions: header, nav, main, section, and footer. Fragment links such as #about navigate to an element with the matching id. A mailto link identifies an email destination and opens an email action in a configured client.

## 5. Algorithm / Procedure

1. Create about-me.html with a header name, About and Contact navigation links, an empty main, and an empty footer.

2. Add an about section with id about, an h2, and a paragraph.

3. Give the footer id contact and add a paragraph with a mailto email link.

## 6. Program / Queries / Commands

### Task Final cumulative page — about-me.html

```html
<!-- Name: LOKESH SHUKLA | Roll Number: 2510303281 | Assignment: BCS352 Lab 7 -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>About Me</title>
</head>
<body>

    <header>
        <h1>LOKESH SHUKLA</h1>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="about">
            <h2>About me</h2>
            <p>Hello! I am a B.Tech CSE student. I enjoy learning HTML and CSS.</p>
        </section>
    </main>

    <footer id="contact">
        <p>Email: <a href="mailto:lokeshshukla083@gmail.com">lokeshshukla083@gmail.com</a></p>
    </footer>

</body>
</html>
```


## 7. Input

### Task 1
Your name and the fragment destinations #about and #contact.

### Task 2
A short paragraph about yourself.

### Task 3
Your email address.

## 8. Output

The repository has one screenshot showing the final page after all three cumulative tasks.

### Final page after Tasks 1–3

![Final About Me page](Lab%207%20-%20Task1.png)
## 9. Result

The final About Me page shows the student name, About and Contact navigation, a short about paragraph, and a clickable email address. The Contact link targets the footer.

## 10. Viva-Voce Questions

1. What is semantic HTML?
2. How does a fragment link locate a section?
3. What does mailto: do?



