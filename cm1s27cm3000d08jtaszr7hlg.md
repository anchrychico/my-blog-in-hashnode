---
title: "ACTIVITY 20:Research BEM-Block, Element, Modifier-Architecture"
datePublished: Wed Oct 02 2024 16:05:47 GMT+0000 (Coordinated Universal Time)
cuid: cm1s27cm3000d08jtaszr7hlg
slug: activity-20research-bem-block-element-modifier-architecture

---

Practice:

Create an HTML structure using BEM naming conventions and write CSS to style it.

```xml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BEM Example</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1 class="header__title">My Project in SIA 102</h1>
        <nav class="header__nav">
            <ul class="nav">
                <li class="nav__item"><a class="nav__link" href="#">Home</a></li>
                <li class="nav__item"><a class="nav__link" href="#">About</a></li>
                <li class="nav__item"><a class="nav__link" href="#">Services</a></li>
                <li class="nav__item"><a class="nav__link" href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main class="main">
        <section class="section section--primary">
            <h2 class="section__title">Welcome to My Project in SIA 102</h2>
            <p class="section__text">This is a simple example of a webpage using BEM conventions.</p>
        </section>
        <section class="section section--secondary">
            <h2 class="section__title">Featured Services</h2>
            <div class="services">
                <div class="service service--highlighted">
                    <h3 class="service__title">Service 1</h3>
                    <p class="service__description">Description of Service 1.</p>
                </div>
                <div class="service">
                    <h3 class="service__title">Service 2</h3>
                    <p class="service__description">Description of Service 2.</p>
                </div>
                <div class="service">
                    <h3 class="service__title">Service 3</h3>
                    <p class="service__description">Description of Service 3.</p>
                </div>
            </div>
        </section>
    </main>
    
    <footer class="footer">
        <p class="footer__text">© 2024 My Project in SIA 102. All rights reserved.</p>
    </footer>
</body>
</html>
```

```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

.header {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
}

.header__title {
    margin: 0;
}

.header__nav {
    margin-top: 10px;
}

.nav {
    list-style-type: none;
    padding: 0;
}

.nav__item {
    display: inline;
    margin-right: 15px;
}

.nav__link {
    color: white;
    text-decoration: none;
}

.nav__link:hover {
    text-decoration: underline;
}

.main {
    padding: 20px;
}

.section {
    margin-bottom: 20px;
}

.section--primary {
    background-color: #f9f9f9;
    padding: 15px;
    border-radius: 5px;
}

.section--secondary {
    background-color: #e9e9e9;
    padding: 15px;
    border-radius: 5px;
}

.section__title {
    margin: 0;
}

.section__text {
    margin: 10px 0;
}

.services {
    display: flex;
    gap: 15px;
}

.service {
    background-color: #ffffff;
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 10px;
    flex: 1;
}

.service--highlighted {
    border: 2px solid #4CAF50;
}

.service__title {
    margin: 0;
}

.footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: relative;
    bottom: 0;
    width: 100%;
}

.footer__text {
    margin: 0;
}
```

Here's the Output

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1727884990149/5de49c77-cf30-4f05-afbb-1765fddb4749.jpeg align="center")

**Explanation:**

BEM Structure: The class names follow the BEM convention, where:

**Block**: Represents a high-level component (e.g., header, main, section, footer).

**Element**: A part of a block that performs a specific function (e.g., header\_\_title, nav\_\_item, section\_\_title).

**Modifier**: A variant of a block or element that changes its appearance or behavior (e.g., section--primary, service--highlighted).