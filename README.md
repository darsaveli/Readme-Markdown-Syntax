# Readme Markdown Syntax
Markdown is a syntax for styling all forms of writing on the GitHub platform.
Mostly, it is just regular text with a few non-alphabetic characters thrown in, like ```git # or * ```

You can use Markdown most places around GitHub:

1. Gists
2. Comments in Issues and Pull Requests
3. Files with the .md or .markdown extension
4. For more information, see “Writing on GitHub” in the GitHub Help.

___

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

___

### Font

```git
*Italics*
_This will also be italic_
**Bold text**
__This will also be bold__
***Bold and Italics***
_You **can** combine them_
~~Striked Text~~
***~~Italic, bold, and strikethrough1~~***	
```

*Italics* <br>
_This will also be italic_<br>
**Bold Text**<br>
__This will also be bold__<br>
_You **can** combine them_<br>
***Bold and Italics***<br>
~~Striked Text~~
***~~Italic, bold, and strikethrough1~~***	
___

### Lists

> Unordered 

```git
* Item 1
* Item 2
  * Item 1a
  * Item 2a
     * Item 1b
     * Item 2b
```

* Item 1
* Item 2
  * Item 1a
  * Item 2a
     * Item 1b
     * Item 2b

OR
`- Item 1`
- Item 1

> Ordered 

```git
1. First
2. jhg
   1. Second
   2. jhg
      1. Third
      2. jhg
```

1. First
2. jhg
   1. Second
   2. jhg
      1. Third
      2. jhg

___

### Links

```git
* [Link with more info with various formatting options](https://docs.github.com/en/github/writing-on-github "more info")
* https://www.google.com/
* <https://www.google.com/>
```

* [Link with more info with various formatting options](https://docs.github.com/en/github/writing-on-github "more info")
* https://www.google.com/
* <https://www.google.com/>

### Link Label 
```git
[My GitHub][GitHubLink]
```
[My GitHub][GitHubLink]

You may define your link label anywhere in the document.
```git
e.g. put on bottom: 

--------------------------------
[GitHubLink]:https://github.com/darsaveli
```

### Links to the URLs in a repository

```git
[Example document](/example/example.md)
```

[Example document](/example/example.md)

```git
[example](./example)
```

[example](./example)

___

### Inserting Images or Gifs using links

```git
![alt](URL "title")
```

alt and title are corresponding to the alt and title attributes in the HTML (all can be omitted)：
- alt in square bracket indicates the replacement text when the image fails to display
- parenthesis contains image source
- title in quotes indicates the text to display when the mouse hovers over the image

Nite: Dropping the image to the readme file will upload it automatically with this syntax;
It's the same as links, but add an exlamation mark (!) before opening square bracket;
Image source can be either a location from the local machine or any valid image URL;

>Example

```git
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github logo") 
```
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github logo") 

### Resize images/Gifs
```
<img src="https://github.com/darsaveli/Mariam/blob/main/1479814528_webarebears.gif" width="385px" align="center">
```
<img src="https://github.com/darsaveli/Mariam/blob/main/1479814528_webarebears.gif" width="385px" align="center">

You can use HTML tags like width="385px", hight="876px", align="center", etc depending what you need. In this case this gif was once uploaded to the repository and the link was taken from there.

Other options to resize: 
- `![](https://  link | width=100)`

___

### Linking Image/Gif
To open another webpage when image is clicked, enclose the Markdown for the image in brackets, and then add the link in parentheses.

```
![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png "Github Logo") 
(https://github.com/)
```

 ![Octocat](https://user-images.githubusercontent.com/81953271/124010886-b571ca80-d9df-11eb-86ac-b358c48ac6aa.png) 
(https://github.com/)
___

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

### Align
You may specify alignment like this:
```git
| Align left | Centered  | Align right |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
```
| Align left | Centered  | Align right |
| :------------ |:---------------:| -----:|
| aaa     | bbb | ccc |

___

### CheckBox

```git
* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected
```


* [ ] Checkbox1

* [ ] Checkbox2

* [x] Checkbox selected

You may use this syntax in GitHub's issue to check or uncheck the checkbox in real time without having to modify the original version of the issue.

___

### Quoting Text

```git
> This is a block quoted text
```

> This is a block quoted text

### Multi-level blockquotes
```
> Asia
>> China
>>> Beijing
>>>> Haidian
>>>>> Tsinghua
```
#### Look like
> Asia
>> China
>>> Beijing
>>>> Haidian
>>>>> Tsinghua

* These are fenced code blocks

___

### Text highlighting

```git
`linux` `ubuntu`
```
Using a pair of backquotes is suitable for making tags for articles
`linux` `ubuntu`

___

### Horizontal Line

```git
***
___
--- 
```

All three will be rendered as:
___
p.s. 
```git
<hr> works too
```
___

### Code Block
There are three ways to add code in markdown
1. Inline Code (single backtick)
2. Whitespace

```git
    `this` is an example of inline code.
```
    four spaces work too!
    
3. Fenced code blocks
With GFM you can wrap your code with three back quotes to create a code block without the leading spaces. Add annoptional language identifier and your code will get syntax highlighting.

```Java
public static void main(String[]args){} //Java
```

```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```

___

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
      "firstName": "A",
      "lastName": "B
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
  "firstName": "A",
  "lastName": "B",
  "age": 18
}
```
___

### diff syntax

In the version control system, the function of diff is indispensable, i.e., the addition and deletion of a file content is displayed.
The diff effect that can be displayed in GFM. Green is for new, while red is for deleted.
#### Syntax
The syntax is similar to code [fenced code blocks](#fenced-code-blocks), except that the diff is written after the three backticks.
And in the content, the beginning of `+ ` indicates the addition, and the beginning of `- ` indicates the deletion.

```git
```diff
+ Hello world!
- This is useless.
```
```

```diff
+ Hello world!
- This is useless.
```
___

### Break between lines

```git
<br>
```
___

### Visible markdown characters
 
```git
```git
 * __ <br> etc ```
```
___

### Multi-line text

    aaa,
    sss,
    ddd!

Add 1 tab or 4 spaces at the beginning of several lines of text.

OR

Use three backticks:

```
asd,
sfd,
wer!
```
This syntax can also be used for code highlighting

___

### Comments in Markdown

```git
<!-- comment written in markdown -->
```
They will be invisible on readme
___

### Emoji
GitHub supports emoji!
```git
:grinning:	or just place the emoji 😀
```
:grinning:	or just place the emoji 😀

To see a list of every image Github supports, check out the [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

___

### Anchor
In fact, each title is an anchor, similar to the HTML anchor (`#`), e.g.

|Syntax|Look like|
|---|---|
|`[Back to top](#readme)`|[Back to top](#readme)|

Note that all the letters in the title are converted to **lowercase letters**.

--------------------------------
[GitHubLink]:https://github.com/darsaveli
