# 1. HTML Structure, Tags and Attributes

> _Welcome to the second lesson of HTML for Absolute Beginners 2025! In this video, we'll cover the Structure of HTML, Categories of Tags and Attributes._

## HTML Structure

Any HTML structure contains 3 tags:

- HTML - The wrapper or root element of the html file.
- HEAD - Inside head tag all the meta tags are included such as Title, meta data, links etc.
- BODY - The body tag contains the main content which is displayed on the web page.

```html
<html>
	<head></head>
	<body></body>
</html>
```

## Types of tags in HTML:

- #### **Paired Tags** - div, ul, ol, li etc
- #### **Self-Closing Tags** - input, br, hr, img etc
- #### **Formatting Tags** - i, b etc
- #### **Media Tags** - audio, video, img etc
- #### **Interactive Tags** - button, radiobutton, checkbox etc
- #### **Semantic Tags(Important)** - header, footer, nav, section etc

## Attributes

Attributes are nothing but the data of an element or a tag. In other words, attribute justifies the data of the element or tag.

For example:

```html
<html>
	<head>
		<title>Attributes</title>
	</head>
	<body>
		<h1 class="heading">This is a heading tag.</h1>
		<img src="my-image-path.png" />
		<a href="www.google.com">Click here to visit Google</a>
	</body>
</html>
```

- #### **In h1 tag** - "class" is an attribute.
- #### **In img tag** - "src" is an attribute. src means the source/path of a image file.
- #### **In a tag** - "href" is an attribute. href means Hyper Reference, the link of a webpage where you want to visit when clicking.

## Concept of Div Soup:

> _The "div soup" is basically a problem. Its a bad practice which mostly the beginners do while learning HTML. When you use multiple "div" tags unnecessarily in place of other tags which does not make sense then that part of code is said to be a div soup._

For example:

```html
<html>
	<head>
		<title>Div Soup</title>
	</head>
	<body>
		<div>
			<div>
				<div>Heading 1</div>
			</div>
			<div>Paragraph</div>
		</div>
	</body>
</html>
```

here you can clearly see the problems.

- The code is un-readable.
- Its very bad for SEO.
- It will be very hard to debug.

## How to prevent the Div Soup?

To prevent the Div soup, we use the semantic tags and the example is shown below

```html
<html>
	<head>
		<title>My First Webpage</title>
	</head>
	<body>
		<header>
			<nav>The navigation bar here</nav>
		</header>
		<section>
			<h1>Heading 1</h1>
			<p>Paragraph</p>
		</section>
		<footer>Copyright@2025</footer>
	</body>
</html>
```

## 🎥 Course Resources

### 📺 Watch this lesson: HTML Structure, Tags and Attributes | HTML for absolute beginners in 2025 | #2

> ### Full Course Playlist: **_[Watch the full video here](https://youtu.be/GBYNWHgPO_E)_**
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
