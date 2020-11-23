# **README CHEATSHEET 🚀**

## **Basics**

### 1. Headings 

To create a heding in Readme we need to use  #. Size of headings can be change by adding multiple  `#` Together. The greate the number of `#` is the smaller the heading is.
```
Symbol    Tag       Example
`#`       <h1>      # h1 heading
`##`      <h1>      # h2 heading
`###`     <h4>      # h3 heading
`####`    <h4>      # h4 heading
```

### 2. Bold and Italic Text
We need to Use `*` Symbol. 
Actions     Syntax          Example
Bold -      `**Text**`      **Bold Text**

Italic -    `*Text*`        *Italic Text*

Bold+Italic - `***Text***`  ***Bold+Italic Text***

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

### 4. Adding Links To Text
Syntax:
`[Text](Link)`

Example:
[Sample Text](https://github.com/Abhayparashar31)

### 5. Adding Images
Steps:
1. Put Your Image In The Same Repo.
2. Open Image And Copy The Path
3. Syantax: `![Alt Text](Path_to_image)`

![Github Logo](https://github.com/Abhayparashar31/Readme-Cheatsheet/blob/main/github-logo.png)

### 6. BlockQuotes

BlockQuotes Can be inserted Using `>`

Example:
> This is a sample BlockQuote

### 7. Inline Code

To add Inline Code You Need to use **Grave Accent** symbol.

Example:
This is an example of `inline code` in Github Readme.

### 8. Syntax highlighting
```
For i in range(0,100):
  if i>50:
      print(i)
  elif i<50:
      print(i*i)
```


### 9. Horizontal Rule
To add a Horizontal Rule In Readme we can use `---` or `***` .

***

## **Advance**

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
    <img src="github-logo.png" alt="Logo" width="80" height="80">
  </a>
```
<a href="https://github.com/Abhayparashar31/Readme-Cheatsheet">
  <img src="github-logo.png" alt="Logo" width="80" height="80">
</a>
