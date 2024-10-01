---
title: "Activity 18: Research HTML"
datePublished: Tue Oct 01 2024 11:10:19 GMT+0000 (Coordinated Universal Time)
cuid: cm1qc7izj000809l84ndrgku1
slug: activity-18-research-html

---

Instructions:

Basic HTML Elements:

Write an HTML document and use the following:

Headings: Add headings like &lt;h1&gt;, &lt;h2&gt;, &lt;h3&gt;, etc.

Paragraph: Use &lt;p&gt; for text blocks.

Lists:

Unordered List: Use &lt;ul&gt; for bullet points.

Ordered List: Use &lt;ol&gt; for numbered lists.

Table: Add a table with &lt;table&gt;, &lt;tr&gt;, &lt;th&gt;, and &lt;td&gt;.

Semantic HTML:

Use meaningful tags like &lt;header&gt;, &lt;footer&gt;, &lt;article&gt;, &lt;section&gt;, and &lt;nav&gt; to organize your web page.

```xml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic HTML Document</title>
</head>
<body>

<header>
    <h1>Welcome to My Web Page</h1>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="about">
    <h2>About This Page</h2>
    <p>This is a simple HTML document that demonstrates various HTML elements.</p>
</section>

<section id="services">
    <h2>Our Services</h2>
    <h3>Services We Offer:</h3>
    <ul>
        <li>Web Development</li>
        <li>Graphic Design</li>
        <li>SEO Optimization</li>
    </ul>

    <h3>Why Choose Us?</h3>
    <ol>
        <li>Experienced Team</li>
        <li>Customer Satisfaction</li>
        <li>Affordable Prices</li>
    </ol>
</section>

<section>
    <h2>Our Team</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Position</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>Web Developer</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>Graphic Designer</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Emily Johnson</td>
            <td>SEO Specialist</td>
            <td>emily@example.com</td>
        </tr>
    </table>
</section>

<footer>
    <h2>Contact Us</h2>
    <p>If you have any questions, feel free to reach out via email at info@example.com.</p>
</footer>

</body>
</html>
```

Explanation

Header and Navigation: Organizes the site’s main sections.

Sections: Clearly defines content areas.

Lists: Provide structured information.

Table: Displays data in an organized manner.

Headings: &lt;h1&gt;, &lt;h2&gt;, &lt;h3&gt; for various sections.

Paragraphs: &lt;p&gt; for text content.

Lists: &lt;ul&gt; for an unordered list and &lt;ol&gt; for an ordered list.

Table: &lt;table&gt;, &lt;tr&gt;, &lt;th&gt;, and &lt;td&gt; for displaying tabular data.

Semantic HTML: Used &lt;header&gt;, &lt;nav&gt;, &lt;section&gt;, and &lt;footer&gt; to give structure and meaning to the document.

.