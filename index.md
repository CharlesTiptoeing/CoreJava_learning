## CoreJava_learning


### 3rd March



```markdown
Core Java Page 86

# Traverses a string

int cp = sentence.codePointAt(i);
    if (Character.isSupplementaryCodePoint(cp)) i += 2;
    else i++;
    
## Move backforwards

i--;
    if (Character.isSurrogate(sentence.charAt(i))) i--;
    int cp = sentence.codePointAt(i);
    
### Easier way

int[] codePoints = str.codePoints().toArray();

>use **codePoints** to yield a stream of **int** values, turn the stream into array

### Turn an array of code ponits into arrays

String str = new String(codePoints, 0, codePoints.length);



1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/CharlesTiptoeing/CoreJava_learning/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
