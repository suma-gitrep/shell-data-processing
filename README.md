# Shell Data Processing 

The command used to get your data : curl "https://americanliterature.com/author/oscar-wilde/poem/the-disciple" -0 data.txt
<br>
The comand which is used to sort the data is : tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr
<br>
[Data-file](https://github.com/suma-gitrep/shell-data-processing/blob/master/data.txt)
<br>
[Result-file](https://github.com/suma-gitrep/shell-data-processing/blob/master/result.txt)


## Basic commands 

- creates a new directory

```Bash 
mkdir 
``` 

- deletes the specified empty directory

```Bash 
 rmdir 
 ``` 

- deletes a specified directory containing files
 ```Bash 
 rm  
 ``` 

- shows the current working directory
```Bash 
pwd 
``` 

- displays the contents of file
```Bash 
 cat 
 ``` 

## Markdown Syntax

- Heading - To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level.


```Bash
# H1 - Heading level 1
## H2 - Heading level 2
### H3 - Heading level 3
#### H4 - Heading level 4

```
- **Bold** - To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

```Bash 
**bold text**
```
- *italicized text* - To italicize text, add one asterisk or underscore before and after a word or phrase. 
```Bash
*italicized text*
```
- > Blockqoutes -To create a blockquote, add a > in front of a paragraph.
```Bash
> Sample text here.
```
- Ordered Lists - To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.
```Bash
1. First item
2. Second item
3. Third item
4. Fourth item
```
- Unordered Lists - To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.
```Bash
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item
```
