# LyCheat - Markdown!

## Basic Syntaxes  

### Format Text

#### Bold \ Italics \ Strikethrough Style

\*\*TEXT\*\*  for bold **text** \
\*TEXT\*  or \_TEXT\_ for italics *text* \
\~\~TEXT\~\~ for strike through ~~TEXT~~ 

##### Code View 
put text in \` and \` e.g. 
` My Code is here'  \
Sandwitch multilien code under \``` and \``` e.g. \
\```ruby  
CODE line 1; \
CODE line 1; \
CODE line 1; \
Code line 4; \
\``` \
Above syntaxes can be used in combination as well

### Heading

For H1 to Hn, generally avoid using H1 or H6. H1 is largest font
alternate is to write == under heading one text and --- under heading 2 text

### Link
#### External links
\[text to display\]\(url\)  \
We can use font italics/bold etc to format text to display also one can use full heading or part of theading to use as link

#### Relative link or Internal links : reference link \
one can also link a lcoal file \
\[open Local file\]\(anotherfile.md\) or \[open Local file\]\(repo/anotherfile.md\)  

#### Section link \
When you want to use link at multiple places. create reference for that in bottom of .md  \
[common ref] : https://www.markdownguide.org/cheat-sheet/ \
[common ref2] : www.google.com 

and write link as above but replacing {link} by [common ref] \
[text to display 1][common ref] \
[text to display 2][common ref1] \
.. \
[text to display 12][common ref1]


### Images
very much like link, only prefixed with ! 

```
![A representation of Octdrey Catburn](http://octodex.github.com/images/octdrey-catburn.jpg)
```
![A representation of Octdrey Catburn](http://octodex.github.com/images/octdrey-catburn.jpg)

### BlockQuotes
start with "> " \
to insert  in same block empty line start with '>' only 
put > on empty line if block quote spans to multiple paragrah

### List 
Unordered - start with *, + or - \
Ordered - start with number followed by . or ) \
checkboxed list - after list syntax i.e. * or - use []/[x] \
* [] 
+ [x] 

### Automated links
GIThub directly converts url or pull request reference numbers to links e.g. VISIT www.google.com will converts to google link

### Table 
Create Table using pipe | and - 
one can format text inside table

### Paragraph 
softbreak using double space at the end of the file

### Emoji
Git hub supports emoji, check emoji ref

### How to add comment 
Put your comment/multiline comment between 
```
<!--
  Here is the comment
  ---- comment can continue
-->
```

### How to fold content
<details style="margin-left: 40px;">
<!--
  <summary><font size="6">To know more unfold me!</font></summary>
  OR 
  <summary><span style="font-size: 16px; font-weight: bold;">To know more unfold me!</span></summary>
-->
<summary><font size="6"><b><I><U>To know more unfold me!</U></I></b></font></summary>
<div style="padding-left: 20px;">
Here is heading and content underneath
<h3> Heading</h3>
<ol>
    <li>Foo</li>
    <li>Bar</li>
  </ul>
</ol>
</div>

### You can fold even code    
```cpp
std::cout << "Hello! so you unfolded!">>
``` 

Note: Font and html listing can be avoided
</details>  


## References
[Github Basic Syntax help](https://help.github.com/en/articles/basic-writing-and-formatting-syntax)   
[Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)   
[Markdown Editor](https://stackedit.io/)
[Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)