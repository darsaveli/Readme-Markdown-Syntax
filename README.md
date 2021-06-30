# Readme Markdown Syntax
Markdown is a syntax for styling all forms of writing on the GitHub platform.
Mostly, it is just regular text with a few non-alphabetic characters thrown in, like ```git # or * ```

You can use Markdown most places around GitHub:

1. Gists
2. Comments in Issues and Pull Requests
3. Files with the .md or .markdown extension
4. For more information, see “Writing on GitHub” in the GitHub Help.


### Headers

```git
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


### Font

```git
*Italics*
_This will also be italic_
**Bold text**
__This will also be bold__
***Bold and Italics***
_You **can** combine them_
~~Striked Text~~
```

*Italics* <br>
_This will also be italic_<br>
**Bold Text**<br>
__This will also be bold__<br>
_You **can** combine them_<br>
***Bold and Italics***<br>
~~Striked Text~~


### Lists(Unordered and Ordered)

Unordered list
```git
* Item 1
* Item 2
  * Item 1a
  * Item 2a
```

* Item 1
* Item 2
  * Item 1a
  * Item 2a

Ordered list
```git
1. Item 1
2. Item 2
    1. Item 1a
    2. Item 2a
```

1. Item 1
2. Item 2
    1. Item 1a
    2. Item 2a

### Links

```git
* [This is a link to more information for structuring the information shared on GitHub with various formatting options](https://docs.github.com/en/github/writing-on-github)
* <https://www.google.com/>
```

* [This is a link to more information for structuring the information shared on GitHub with various formatting options](https://docs.github.com/en/github/writing-on-github)
* <https://www.google.com/>

### Images or Gifs

```
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github Logo") 
```
As same as links, but add an exlamation mark (!) before opening square bracket.  
The square bracket contains `alt` for the image and parenthesis contains image source.  
Image source can be either a location from the local machine or any valid image URL.  
the last part contains additional information about the image shown when use hovers through it.

![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png width="200px" align="center" "Github Logo") 

### Resize images

You can use tags like width="385px" align="right" etc depending what you need.

### Linking Image/Gif
To open another webpage when image is clicked, enclose the Markdown for the image in brackets, and then add the link in parentheses.

```
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github Logo") 
(https://github.com/)
```

 ![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github Logo") 
(https://github.com/)

### Tables

```git
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |
```

|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |

### CheckBox

```git
* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected
```


* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected

### Block Quotes

```git
> This is a block quoted text
```

> This is a block quoted text

### Horizontal Line

```git
***
___
--- 
```

All three will be rendered as:
___

### Code Block
There are three ways to add code in markdown
1. Inline Code (single backtick)
1. Whitespace (Four Spaces Indentation)
1. Fenced Code Block (Three Backticks *or* Tildes)

    `this` is an example of inline code.
    
    '''
    console.log('Used backticks to show snippets')
    '''
    
    console.log('four whitespace works too!')
    
`this` is an example of inline code.
```
console.log('Used backticks to show snippets')
```
    console.log('four whitespace works too!')    

### Syntax Highlighting
If language name is mentioned after the end of first set of backticks, the code snippet will be highlighted according to the language.

    ```js
    console.log('javascript')
    ```
    
    ```python
    print('python')
    ```
    
    ```java
    System.out.println('java')
    ```
       
    ```json
    {
      "firstName": "Kaushal",
      "lastName": "Joshi
      "age": 18
    }
    ```

```js
console.log('javascript')
```

```python
print('python')
```

```java
System.out.println('java')
```

```json
{
  "firstName": "Kaushal",
  "lastName": "Joshi",
  "age": 18
}
```

### Break between lines

```git
<br>
```

### How to make visible characters used for markdown? 
 
```git
```git
 * __ <br> etc ```
```

