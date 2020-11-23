<h1 align='center'>
 README CHEATSHEET 🚀
</h1>
<hr>

<h2 align='center'>
 Basics </h2>
 
### 1. Headings 

To create a heding in Readme we need to use  #. Size of headings can be change by adding multiple  `#` Together. The greate the number of `#` is the smaller the heading is.
```
Symbol    Tag       Example
`#`       <h1>      # h1 heading
`##`      <h1>      # h2 heading
`###`     <h4>      # h3 heading
`####`    <h4>      # h4 heading
`#####`   <h5>      # h5 heading
`######`  <h6>      # h6 heading
```

# h1 heading
## h2 heading
### h3 heading
#### h4 heading
##### h5 heading
###### h6 heading

```
<h1>h1 Heading</h1>
<h4>h4 Heading</h4>
```
<h1> h1 Heading</h1>
<h4> h4 Heading</h4>

<hr>

### 2. Bold and Italic Text
We need to Use `*` Symbol. 

Actions     Syntax          Example

Bold -      `**Text**`      **Bold Text**

Italic -    `*Text*`        *Italic Text*

Bold+Italic - `***Text***`  ***Bold+Italic Text***

<hr>

### 3. Lists

To Create a Unorderedlist we can use `*` or `-` for each list point.

**Example:**
* Bullet Point 1 Using `*`
- Bullet Point 2 Using `-`

To Create a Ordered list we can simply use `1.` and so on.

**Example:**
1. Point 1
2. Point 2
3. Point 3

<hr>

### 4. Adding Links To Text
Syntax:
`[Text](Link)`

Example:
[Sample Text](https://github.com/Abhayparashar31)

<hr>

### 5. Adding Images
Steps:
1. Put Your Image In The Same Repo.
2. Open Image And Copy The Path
3. Syntax: 

`![Alt Text](Path_to_image)`

OR

```
![alt text][logo]

[logo]: path_to_image
```

![Github Logo](https://github.com/Abhayparashar31/Readme-Cheatsheet/blob/main/assets/github-logo.png)

<hr>

### 6. BlockQuotes

BlockQuotes Can be inserted Using `>`

Example:
> This is a sample BlockQuote

<hr>

### 7. Inline Code

To add Inline Code You Need to use **Grave Accent** symbol.

Example:
This is an example of `inline code` in Github Readme.

<hr>

### 8. Syntax highlighting
```python
for i in range(0,100):
  if i>50:
      print(i)
  elif i<50:
      print(i*i)
```

<hr>

### 9. Tables
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

<hr>

### 10. StrikeThrew

```
~~content~~
```
~~content~~ 

<hr>

### 11. Line Break
```
<br/>
or
<br>
```
<br>

<hr>

### 12. Horizontal Rule
To add a Horizontal Rule In Readme we can use `---` or `***` or `<hr>`.

***
<br/>

<h2 align='center'>
 Advance </h2>

### 1. Custom Width and Height Images
To add Height and Width To our Images We can Use Tags From HTML.

Syntax
```
  <a href="LINK_TO_REPO">
    <img src="IMAGE_PATH_INSIDE_REPO" alt="Logo" width="80" height="80">
  </a>
```
Example
```
  <a href="https://github.com/Abhayparashar31/Readme-Cheatsheet">
    <img src="assets/github-logo.png" alt="Logo" width="80" height="80">
  </a>
```
<a href="https://github.com/Abhayparashar31/Readme-Cheatsheet">
  <img src="assets/github-logo.png" alt="Logo" width="80" height="80">
</a>


### 2. Adding GIF
Step 1: Download a GIF From Giphy or Create Your Own GIF

Step 2: Upload GIF to Your Repo

Step 3: Use Custom Width Code and Insert GIF

Example:

<a href="https://github.com/Abhayparashar31/Readme-Cheatsheet">
  <img src="assets/github-gif.gif" alt="Logo" width="150" height="150">
</a>

### 3. Adding External Link / Adding Same Link To Multiple Text

```
[Sampel Text 1][link]
[Sampel Text 2][link]
[Sampel Text 3][link]

[link](ACTUAL_LINK)
```
Example:
[Sampel Text 1][link]
[Sampel Text 2][link]
[Sampel Text 3][link]

[link](https://github.com/Abhayparashar31)


### 4. Adding hyperlinks or Tabs

```
[Basics](#basics)

# Basics
...
...
...
```
### [Basics](#basics)
### [Advance](#advance)


### 5. Markdown Badges

* Single Badges

<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/>

* Multiple Badges Together
<p>
<img src="https://img.shields.io/badge/<handle>%20-%23E4405F.svg?&style=for-the-badge&logo=Instagram&logoColor=white"/>
<img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/>
<img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/>
</p>

> [Check Out All Markdown Badges](https://github.com/Ileriayo/markdown-badges)
> [See All Shield Badges](https://shields.io/)


### 6. Emojis
 Check Out The List Of Emojies [here](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
 
 



