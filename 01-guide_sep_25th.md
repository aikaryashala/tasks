# HTML Basics Guide to complete Tasks

This README will help you understand the essential HTML concepts needed to complete the 5 HTML tasks.

## What is HTML?

HTML (HyperText Markup Language) is the standard language for creating web pages. It uses **tags** to structure and display content in web browsers.

## Basic HTML Document Structure

Every HTML document follows this basic structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Your Page Title</title>
</head>
<body>
    <!-- Your content goes here -->
</body>
</html>
```

- `<!DOCTYPE html>` - Tells the browser this is HTML5
- `<html>` - Root element that wraps all content
- `<head>` - Contains information about the page (not visible to users)
- `<title>` - Sets the page title (appears in browser tab)
- `<body>` - Contains all visible content

## Understanding Tags and Elements

### What are Tags?
Tags are keywords surrounded by angle brackets `< >`. Most tags come in pairs:
- **Opening tag**: `<tagname>`
- **Closing tag**: `</tagname>`

Example: `<p>This is a paragraph</p>`

### Self-Closing Tags
Some tags don't need closing tags:
- `<br>` - Line break
- `<img>` - Image
- `<hr>` - Horizontal rule

## Essential HTML Tags for the Tasks

### 1. Headings
Use `<h1>` to `<h6>` for headings (h1 is largest, h6 is smallest):

```html
<h1>వెంకట రావు (Venkata Rao)</h1>
<h2>About Me</h2>
<h3>My Skills</h3>
```

### 2. Paragraphs
Use `<p>` for regular text paragraphs:

```html
<p>నమస్కారం! I'm a student from Visakhapatnam learning HTML.</p>
```

### 3. Line Breaks
Use `<br>` to create line breaks within text:

```html
<p>Our Campus:<br>
NIT Andhra Pradesh<br>
Tadepalligudem, West Godavari</p>
```

### 4. Lists

#### Unordered Lists (Bullet Points)
```html
<ul>
    <li>I study at Andhra University</li>
    <li>I love Kuchipudi dance</li>
    <li>I enjoy coding and kabaddi</li>
</ul>
```

#### Ordered Lists (Numbered)
```html
<ol>
    <li>2 cups cooked rice</li>
    <li>3 tbsp tamarind paste</li>
    <li>1 tsp turmeric powder</li>
</ol>
```

### 5. Links
Use `<a>` tag with `href` attribute:

```html
<a href="mailto:venkat.rao@gmail.com">Contact me at: venkat.rao@gmail.com</a>
<a href="https://nitandhra.ac.in">Visit our website</a>
```

### 6. Images
Use `<img>` tag with `src` and `alt` attributes:

```html
<img src="tirupati-temple.jpg" alt="Tirumala Temple">
```

- `src` - Path to the image file
- `alt` - Alternative text (shows if image doesn't load, helps accessibility)

### 7. Text Formatting
- `<strong>` - Makes text bold and important
- `<em>` - Makes text italic and emphasized

```html
<p>The most important tags are: <strong>headings</strong> and <em>paragraphs</em></p>
```

## Understanding Attributes

Attributes provide additional information about elements. They go inside the opening tag:

```html
<img src="beach.jpg" alt="RK Beach sunset">
<a href="mailto:info@example.com">Email us</a>
```

Common attributes:
- `src` - Source for images
- `href` - Link destination
- `alt` - Alternative text for images

## HTML Entities (Special Characters)

Some characters have special meaning in HTML, so we use entities to display them as text:

```html
&lt;    displays: <
&gt;    displays: >
&amp;   displays: &
&quot;  displays: "
&nbsp;  displays: non-breaking space
```

Example:
```html
<p>HTML uses special characters like &lt; and &gt; for tags.</p>
```

## Comments in HTML

Use comments to add notes that won't display on the webpage:

```html
<!-- This is a comment -->
<p>This text will show up</p>
<!-- This comment won't show up -->
```

## File Organization

Create separate `.html` files for each task:
- `intro.html` - Personal introduction
- `recipe.html` - Pulihora recipe
- `blog.html` - Tech blog post
- `gallery.html` - AP tourism gallery

## Tips for Success

1. **Always close your tags**: `<p>content</p>` not `<p>content`
2. **Use proper nesting**: `<div><p>text</p></div>` not `<div><p>text</div></p>`
3. **Include alt text for images** for accessibility
4. **Use meaningful file names** like `intro.html` not `page1.html`
5. **Test your pages** by opening them in a web browser
6. **Use proper indentation** to make your code readable

## Getting Started

1. Create a new text file
2. Save it with `.html` extension (e.g., `intro.html`)
3. Start with the basic HTML structure
4. Add your content using the tags learned above
5. Open the file in a web browser to see your webpage

## Common Mistakes to Avoid

- Forgetting to close tags
- Missing quotes around attribute values
- Using the wrong tag for the content type
- Not including the basic HTML document structure