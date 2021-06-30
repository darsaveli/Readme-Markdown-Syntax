# Readme Markdown Syntax
Markdown is a syntax for styling all forms of writing on the GitHub platform.
Mostly, it is just regular text with a few non-alphabetic characters thrown in, like ```git # or * ```

You can use Markdown most places around GitHub:

1. Gists
2. Comments in Issues and Pull Requests
3. Files with the .md or .markdown extension
4. For more information, see “Writing on GitHub” in the GitHub Help.


### Headers

#### Syntax
```git
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

#### Appearance
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6


### Font

#### Syntax
```git
*Italics*
_This will also be italic_
**Bold text**
__This will also be bold__
***Bold and Italics***
_You **can** combine them_
~~Striked Text~~
```

#### Appearance

*Italics*
_This will also be italic_
**Bold Text**
__This will also be bold__
_You **can** combine them_
***Bold and Italics***
~~Striked Text~~


### Lists(Unordered and Ordered)

#### Syntax
Unordered list
```git
* Item 1
* Item 2
  * Item 1a
  * Item 2a
```

#### Appearance
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
#### Appearance
1. Item 1
2. Item 2
    1. Item 1a
    2. Item 2a

### Links

#### Syntax
```git
* [This is a link to more information, in the GitHub Help for structuring the information shared on GitHub with various formatting options](https://docs.github.com/en/github/writing-on-github)
* <https://www.google.com/>
```

#### Appearance
* [This is a link to more information, in the GitHub Help for structuring the information shared on GitHub with various formatting options](https://docs.github.com/en/github/writing-on-github)
* <https://www.google.com/>

### Images
#### Syntax
```
 ![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")
```
As same as links, but add an exlamation mark (!) before opening square bracket.  
The square bracket contains `alt` for the image and parenthesis contains image source.  
Image source can be either a location from the local machine or any valid image URL.  
the last part contains additional information about the image shown when use hovers through it.
#### Appearence
 ![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")
 

### Linking Image
To open another webpage when image is clicked, enclose the Markdown for the image in brackets, and then add the link in parentheses.

#### Syntax
```
 [![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")](https://github.com/)
```

#### Appearance
[![GitHub Logo](https://cdn4.iconfinder.com/data/icons/iconsimple-logotypes/512/github-512.png "GitHub Logo")](https://github.com/)

### Tables

#### Syntax
```git
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |
```

#### Appearance
|Header1|Header2|Header3|
| --- | --- | --- |
| This | is a | table |
| This | is 2nd | row |
| This | is 3rd | row |

### CheckBox

#### Syntax
```git
* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected
```

#### Appearance

* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected

### Block Quotes

#### Syntax
```git
> This is a block quoted text
```

#### Appearance
> This is a block quoted text

### Horizontal Line
#### Syntax
```git
***
___
--- 
```
#### Appearance
All three will be rendered as:
___

### Code Block
There are three ways to add code in markdown
1. Inline Code (single backtick)
1. Whitespace (Four Spaces Indentation)
1. Fenced Code Block (Three Backticks *or* Tildes)

#### Syntax
    `this` is an example of inline code.
    
    '''
    console.log('Used backticks to show snippets')
    '''
    
    console.log('four whitespace works too!')
    
#### Appearance
`this` is an example of inline code.
```
console.log('Used backticks to show snippets')
```
    console.log('four whitespace works too!')    

### Syntax Highlighting
If language name is mentioned after the end of first set of backticks, the code snippet will be highlighted according to the language.

#### Syntax
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

#### Appearance 
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

#### Break between lines

Add
```git
<br>
```
between lines to insert a break

#### How to make visible characters used for markdown? 

Use 
```git
```git
 * __ <br> etc.
```
```

