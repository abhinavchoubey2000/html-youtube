# 3. Headings, Paragraph, Lists and Links

> _Welcome to the third lesson of HTML for Absolute Beginners 2025! In this video, we'll cover the Content Elements of HTML which are Headings, Paragraph, Lists and Links._

## Headings

> There are 6 types of headings in HTML. The numberings of heading starts from 1 to 6 which is higher to lower and it is shown below in the example:

code:

```html
<html>
	<head>
		<title>Headings</title>
	</head>
	<body>
		<h1>Heading-1</h1>
		<h2>Heading-2</h2>
		<h3>Heading-3</h3>
		<h4>Heading-4</h4>
		<h5>Heading-5</h5>
		<h6>Heading-6</h6>
	</body>
</html>
```

output:

# Heading-1

## Heading-2

### Heading-3

#### Heading-4

##### Heading-5

###### Heading-6

## Paragraph

>A paragraph tag in HTML is used to write paragraphs and it is an block element which means even if you write "A" in paragraph tag then that element will the the full width.

For example:

```html
<html>
	<head>
		<title>Paragraph</title>
	</head>
	<body>
		<p>This is a paragraph tag here you can write paragraph.</p>

		<p>A</p>
		<!-- Even if only A is written still it will take its full width, means any tag which is written after this p tag will be rendered in next line -->

		<p>B</p>
		<!-- This B will be rendered in next line -->
	</body>
</html>
```

## Span

>A span tag in HTML is used to write the inline texts means, it is an inline element. If you write multiple span tags then it will be rendered in same line. It is an inline element.

For example:

```html
<html>
	<head>
		<title>Span</title>
	</head>
	<body>
		<span>This is a span tag</span>

		<span>This text will be rendered in same line</span
		><!-- Hence it is an inline element, even you give spaces then also all the text will be printed in same line  -->
	</body>
</html>
```

## Lorem:

> _Lorem is one of the emit abbreviation. It is used for generating the random words and sentences._

- for words:

```html
<span>lorem5</span>
<!-- Generates 5 random words  -->
```

- for sentences:

```html
<p>lorem*5</p>
<!-- Generates 5 random paragraphs  -->
```

## Differnce between `<p>` tag and `<span>` tag

>It very simple, the paragraph tag is an Block element whereas the span tag is an inline element.

## Formatting Tags

### `<i>` tag:

> `<i>` tag is used to make the text in italic format.

#### example:

```html
<html>
	<head>
		<title>Italic Format</title>
	</head>
	<body>
		<p>My name is <i>Abhinav</i></p>
	</body>
</html>
```

### `<b>` and `<strong>` tag:

> `<b>` and `<strong>` tag is used to make the text in bold format.

#### example:

```html
<html>
	<head>
		<title>Bold Format</title>
	</head>
	<body>
		<p>My name is <b>Abhinav</b></p>
		<p>My name is <strong>Abhinav</strong></p>
	</body>
</html>
```

### `<u>` tag:

> `<u>` tag is used to add a underline on the text.

#### example:

```html
<html>
	<head>
		<title>Underline</title>
	</head>
	<body>
		<p>My name is <u>Abhinav</u></p>
	</body>
</html>
```

### `<mark>` tag:

> `<mark>` tag is used to hightlight the text.

#### example:

```html
<html>
	<head>
		<title>Highlight</title>
	</head>
	<body>
		<p>My name is <mark>Abhinav</mark></p>
	</body>
</html>
```

## Lists

- ### Un-Ordered Lists

  >An un-ordered list are that category of lists where the lists items are rendered with bullet points. Types of bullets are as follows:

  - #### Disc - ●
  - #### Circle - ○
  - #### Square - ■

  Example

  ```html
  <html>
  	<head>
  		<title>Un-Ordered Lists</title>
  	</head>
  	<body>
  		<!-- Type Disc -->
  		<ul style="list-style-type: disc;">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>

  		<!-- Type Circle -->
  		<ul style="list-style-type: circle;">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>

  		<!-- Type Square -->
  		<ul style="list-style-type: square;">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>
  	</body>
  </html>
  ```

- ### Ordered Lists

  >An ordered list are that category of lists where the lists items are rendered with orders like numberings, aphabets etc. Types of order are as follows:

  - #### 1 - 1,2,3
  - #### a - a,b,c
  - #### A - A,B,C
  - #### I - I,II,III
  - #### i - i,ii,iii

  Example

  ```html
  <html>
  	<head>
  		<title>Ordered Lists</title>
  	</head>
  	<body>
  		<!-- Type 1 -->
  		<ul type="1">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>

  		<!-- Type a -->
  		<ul type="a">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>

  		<!-- Type A -->
  		<ul type="A">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>

  		<!-- Type I -->
  		<ul type="I">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>

  		<!-- Type i -->
  		<ul type="i">
  			<li>Item-1</li>
  			<li>Item-2</li>
  			<li>Item-3</li>
  		</ul>
  	</body>
  </html>
  ```

## Links

>To link one page with other we use `<a>` tag. The meaning of a is Anchor.

For example:

```html
<html>
	<head>
		<title>Link</title>
	</head>
	<body>
		<!-- Open the page in same tab -->
		<a href="https://www.google.com">Click here to visit google</a>
		<!-- Open the page in other tab -->
		<a href="https://www.google.com" target="_black"
			>Click here to visit google</a
		>
	</body>
</html>
```

## 🎥 Course Resources

### 📺 Watch this lesson: HTML Headings, Paragraph, Lists and Links | HTML for absolute beginners in 2025 | #3

> ### Full Course Playlist: **_[Watch the full video here](https://youtu.be/rjD_CfZmjHc?si=TP6Wf1VNn0xuKmsP)_**
>
> ### Follow me on **_[Instagram](https://www.instagram.com/iam_abhinav_chaturvedi)_**
>
> ### Connect with me on **_[LinkedIn](https://www.linkedin.com/in/abhinavchoubey2002)_**

## 🚀 Ready for the Journey?

> Thanks for joining me on this HTML learning adventure!
> Get ready to become a successful developer. Your journey starts now!

> See you in the next video where we'll dive deeper into HTML elements and start building our first real webpage.
> Let's code! 💻✨

> ⭐ Don't forget to star this repository and subscribe to the YouTube channel for more industry-standard web development content!
