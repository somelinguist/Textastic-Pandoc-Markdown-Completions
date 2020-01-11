# Pandoc markdown completions for Textastic

## Installation 

Copy the file `pandoc.json` to the folder `#Textastic/CodeCompletion` in the document root of Textastic. Restart Textastic.

See the [Pandoc manual](https://pandoc.org/MANUAL.html#pandocs-markdown) for a description of Pandoc's version of markdown.

## Supported markdown snippets/completions

````
### Inline

*emphasis* _emphasis_
**stong**. __strong__
~~strikethrough~~

### Links
[text](link)
[text][label]

### Images
![alttext](img)

### Unordered list continuation

+ one 
+ two

- one
- two

* one
* two
    * one
    * two

### Task lists    
- [ ] Do
- [ ] This
- [x] That
    - [ ] First
    - [ ] Second

### Code blocks

```lang
code
```

~~~lang
code
~~~

### Footnotes
Something^[inline note].

Something else[^id].

[^id]: note

````
