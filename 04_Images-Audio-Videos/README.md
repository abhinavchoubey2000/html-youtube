# 4. Images, Audios and Videos - Media Tags

> _Welcome to the fourth lesson of HTML for Absolute Beginners 2025! In this video, we'll cover the Media Tags of HTML which are Images, Audios and Videos._

## Image

> To use images in HTML we use `img` tag. It contains several attributes which are as follows:

- **src** - This attribute is used to give the source of the file which can be a url or file path.
- **alt** - This attribute is used to the alternative text, in case of image failure this text will be displayed if the image is not present.
- **height** - This attribute is used to give the height of the image in pixels in order to resize the image.
- **width** - This attribute is used to give the width of the image in pixels in order to resize the image.

### There are two ways by which we can insert images:-

By giving local path of your image:

```html
<html>
	<head>
		<title>Image - Using Path</title>
	</head>
	<body>
		<img
			src="static/elephant.jpg"
			alt="Group of Elephants"
			height="700"
			width="1360"
		/>
	</body>
</html>
```

By giving url of the image:

```html
<html>
	<head>
		<title>Image - Using URL</title>
	</head>
	<body>
		<img
			src="https://cdn.pixabay.com/photo/2025/09/03/13/33/cat-9813484_960_720.jpg"
			alt="Group of Elephants"
			height="700"
			width="1360"
		/>
	</body>
</html>
```

## Audio

> To use audios in HTML we use `audio` tag. It contains several attributes which are as follows:

- **src** - This attribute is used to give the source of the file which can be the file path.
- **controls** - This attribute is used to add the controls to play or pause the audio. If this attribute is not passed the your audio will not be visible on your web page.

### Why to use seperate `<source>` tag instead of _src_ attribute?

> We use the `<source>` tag to get support of cross browsers. There is not always will be the case where the audio format you have chosen will be supported to every browser. Thats why we use `<source>` tag to give multiple formats of same file. In case of _src_ attribute we can only give one format not multiple.

- using `<audio>` with src attribute:

  ```html
  <html>
  	<head>
  		<title>Audio - src attribute</title>
  	</head>
  	<body>
  		<audio src="static/sound.mp3" controls />
  	</body>
  </html>
  ```

  here you can clearly see that we have given the src attribute but we can only use it once not multiple time. So if any browser which does not support mp3 file then there will be a and your audio will not going to play.

- using `<audio>` tag with `<source> tag`:

  ```html
  <html>
  	<head>
  		<title>Audio - source tag</title>
  	</head>
  	<body>
  		<audio controls>
  			<source src="static/sound.mp3" type="audio/mp3" />
  			<source src="static/sound.wav" type="audio/wav" />
  			This audio is not supported in any browser.
  		</audio>
  	</body>
  </html>
  ```

  here you can clearly see now we are using `<source>` tag which mean if any browser does not support the mp3 file then it will try to play wav file and if any of the file is not supported the it will display the default text given which is _This audio is not supported in any browser_.

## Video

> To use audios in HTML we use `video` tag. It contains several attributes which are as follows:

- **src** - This attribute is used to give the source of the file which can be the file path.
- **controls** - This attribute is used to add the controls to play or pause the video. If this attribute is not passed the your video will be visible as image.
- **autoplay** - This attribute is used to play your video automaticly when the page is loaded. Even if you do not provide the controls attribute then also your will be played.
- **loop** - As the name tells, this attribute loops your video.
- **height** - Just like image, this attribute is used to give the height of the video in pixels in order to resize the video.
- **width** - Just like image, this attribute is used to give the width of the video in pixels in order to resize the video.

`video` tag only with controls attribute:

```html
<html>
	<head>
		<title>Video - Controls attribute</title>
	</head>
	<body>
		<video controls height="500" width="700">
			<source src="static/dog.mp4" type="video/mp4" />
			<source src="static/dog.mkv" type="video/mkv" />
			This video is not supported in any brower.
		</video>
	</body>
</html>
```

`video` tag with autoplay and loop attributes, no controls:

```html
<html>
	<head>
		<title>Video - Autoplay and loop attributes, no controls</title>
	</head>
	<body>
		<video autoplay loop height="500" width="700">
			<source src="static/dog.mp4" type="video/mp4" />
			<source src="static/dog.mkv" type="video/mkv" />
			This video is not supported in any brower.
		</video>
	</body>
</html>
```

`video` tag with controls and loop attributes, no autoplay:

```html
<html>
	<head>
		<title>Video - Controls and loop attributes, no autoplay</title>
	</head>
	<body>
		<video controls loop height="500" width="700">
			<source src="static/dog.mp4" type="video/mp4" />
			<source src="static/dog.mkv" type="video/mkv" />
			This video is not supported in any brower.
		</video>
	</body>
</html>
```

## IFrame:

> _IFrame is used to embed any other HTML page. It can be any web resource like maps, videos or documents._

- Example of Youtube Video IFrame:

```html
<html>
	<head>
		<title>IFrame - Youtube Video</title>
	</head>
	<body>
		<iframe
			width="560"
			height="315"
			src="https://www.youtube.com/embed/GBYNWHgPO_E?si=YsO8RGy_XA68k90K&amp;controls=0"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			referrerpolicy="strict-origin-when-cross-origin"
			allowfullscreen
		></iframe>
	</body>
</html>
```

- - Example of Google Maps IFrame:

```html
<html>
	<head>
		<title>IFrame - Google Maps</title>
	</head>
	<body>
		<iframe
			src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d12282.882610359471!2d77.95418421481173!3d27.22651407089395!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sin!4v1758142515074!5m2!1sen!2sin"
			width="600"
			height="450"
			style="border: 0"
			allowfullscreen=""
			loading="lazy"
			referrerpolicy="no-referrer-when-downgrade"
		></iframe>
	</body>
</html>
```


## 🎥 Course Resources

### 📺 Watch this lesson: Images, Audios and Videos | HTML for absolute beginners in 2025 | #4

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
