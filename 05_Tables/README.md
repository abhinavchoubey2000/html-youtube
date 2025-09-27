# 5. Table Tags

> _Welcome to the fifth lesson of HTML for Absolute Beginners 2025! In this video, we'll cover the Table Tags of HTML._

## Table

> To use tables in HTML we use `table` tag. It contains several child tags which are as follows:

- `<th>` - This tag means Table Head. This is used to create table head/headers.
- `<td>` - This tag means Table Data/Cell. This is used to add data of the tables.
- `<tr>` - This tag means Table Row. This is used as wrapper, used to wrap multiple `td` and `th`.

Basic table example:

```html
<html>
	<head>
		<title>Traditional Table</title>
	</head>
	<body>
		<table border="1">
			<tr>
				<th>Name</th>
				<th>Age</th>
			</tr>
			<tr>
				<td>Abhinav</td>
				<td>88</td>
			</tr>
			<tr>
				<td>Aman</td>
				<td>77</td>
			</tr>
		</table>
	</body>
</html>
```

## Creating Table With Semantic Tags

> We use semantic tags in table because we want to use best practices firstly and for SEO purposes it is a better approach to use semantic tags.

There are 3 main semantic tags for table:

- `<caption>` - This semantic tag is used to give the title or heading of the table.
- `<thead>` - This semantic tag is used to wrap all the head content of the table.
- `<tbody>` - This semantic tag is used to wrap all the data content of the table.

Here is the example of table using semantic tags:

```html
<html>
	<head>
		<title>Table using semantic tags</title>
	</head>
	<body>
		<table border="1">
			<caption>
				Basic Table
			</caption>

			<thead>
				<tr>
					<th>Name</th>
					<th>Age</th>
				</tr>
			</thead>

			<tbody>
				<tr>
					<td>Abhinav</td>
					<td>88</td>
				</tr>
				<tr>
					<td>Aman</td>
					<td>77</td>
				</tr>
			</tbody>
		</table>
	</body>
</html>
```

## Merging cells in Table

> Sometimes there will be a scenario where you need to merge the multiple cells into one, either row wise or column wise.

To merge cells there are two kinds of attribute we can use in `th` and `td` which are as follows:

- **rowspan** - This attribute is used merge multiple rows and it takes value as number. It means if you pass "2" as rowspan then 2 rows will be merged.
- **colspan** - This attribute is used merge multiple columns and it takes value as number. It means if you pass "2" as colspan then 2 columns will be merged.

Here is a basic example:

  ```html
  <html>
  	<head>
  		<title>Table mergin cells</title>
  	</head>
  	<body>
  		<table border="1">
                <caption>User</caption>
                <thead>
                    <!-- Date Of birth | Name -->
                    <tr>
                        <th colspan="3">Date of birth</th>
                        <th rowspan="2">Name</th>
                        <th rowspan="2">Gender</th>

                    </tr>

                    <!-- Day | Month | Year -->
                    <tr>
                        <th>Day</th>
                        <th>Month</th>
                        <th>Year</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>19</td>
                        <td>12</td>
                        <td>2019</td>
                        <td>Abhinav</td>
                        <td>M</td>
                    </tr>
                    <tr>
                        <td>14</td>
                        <td>11</td>
                        <td>2012</td>
                        <td>Aman</td>
                        <td>M</td>
                    </tr>
                </tbody>
            </table>
  	</body>
  </html>
  ```


## 🎥 Course Resources

### 📺 Watch this lesson: [Tables in HTML | HTML for absolute beginners in 2025 | #5](https://youtu.be/AjSd7A2fpfI)

> ### **_[Access to the full playlist](https://www.youtube.com/playlist?list=PL4VKIr7WdJ6AVgGmJjtgn2ZnBUuoHfcL_)_**
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
