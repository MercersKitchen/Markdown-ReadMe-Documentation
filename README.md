# Markdown ReadMe Files Documentation
GitHub & General Markdown language with HTML tags to create a "Read Me" editable in a WYSIWYG like Atom.io.

Introductions to pure Markdown and HTML tags
- See https://www.w3schools.com/htmL/ for more Information

Building a **To Do List**: see additional scripts
- Items marked as *need to be done* or *done*
- No List item is erased
- Tracks progress
- Include dates of copletion if not already included in version control comments and commits

### Outline ###
- PDF Summary Sheet from GitHub
- Supporting Documents and additional reference guides
- Additional Scripts

  Raw Code

  YouTube Videos

  GitHub and other Videos

  Transforming Images

  To Do List

### Summary List of organizing a ReadMe.md or .txt File ###
**See SummaryList.txt** for example planning document

Creating a Formal Outline
-Combining different ordered and unordered notations, with spaces (play with these)

Note
- Able to test and use raw HTML in Markdown
- Test this and see what you find useful.

CAUTION: red highlights in Browser's Editor indicate combination errors

1. Create an Outline with Titles and Section Headers, same as html tags

   a. H1 - H6 (test each tag to view the result)

2. Content

   a. Videos

   b. Images and Logos: Inline & Variable-type reference

      Note: variable reference for logo means change reference once for all copies

3. Adding code emphasis with highlighting

   a. Use single or triple back-tics, `

   b. Name the language for keyword emphasis

   c. OPTION: 4-spaces, using space bar, will do the same as back-tics, not recommended for readability

4. Simple Text and Breaks

   a. Single enter to break in .txt

   b. Double enter to break in .md

5. Bold or Italic Emphasis in text

   a. Bold: *

   b. Italics: _

6. Lists as ordered or unordered

   a. Numbers

   b. Dashes

7. Blockquotes: use > for each line

8. URL Links

   a. Hyperlink text: (Text)[URL]

   b. double backslashes and www are recognized and formatted (blue ink and underlined) as click-able hyperlinks

9. Organizing Sections with a solid gray line: three dashes or asterisks or underscores

---

## Download the PDF Summary Sheet, GitHub ##
https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

---

## Supporting Documents ##
- Straight from GitHub, a description of Markdown ([Click Here](https://guides.github.com/features/mastering-markdown/))
- Excellent online guide for general markdown ([Click Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet))

  Author has other repositories for more programs, including email, that use markdown

---

## Additional Scripts ##

### Raw Code, examples below ###
- add a back-tic, `beginning and end`, for inline highlighting
- add three back-tics, like a comment, at the beginning and end
- name the language being written for coloured keywords
- examples are given below if reading the Markdown, pre-rendered file

### YouTube Video Additions ###
Why YouTube
- Able to use all of YouTube's video editing software
- Able to link the YouTube video to ReadMe.md to save space in GitHub (another demonstration of social media managing)

Empty Script Illustrates
- href URL pointing to
- open a new tab (currently doesn't work)
- image from YouTube beginning video, note img tags are self-closing
- hover over text
- width, height, and border numbers, rendered in GitHub, integers provided

Empty Script Example
```html
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE"
   target="_blank">
<img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
     alt="IMAGE ALT TEXT HERE"
     width="240"
     height="180"
     border="10" />
</a>
```

Concatenating the href URL
- Example URL from YouTube: https://www.youtube.com/watch?v=ThVe4xvNZwI
- Exemplar Additions: https://www.youtube.com/watch?time_continue=0&v=ThVe4xvNZwI
- Pieces and Purpose (CATUION: https, slashes, and www are not included since GitHub auto recognizes these for hyperlink)

  youtube.com : domain name

  watch?v= : script to point to video

  ThVe4xvNZwI : YouTube Name Code for specific video

Concatenating the img URL
- Example URL from YouTube: https://www.youtube.com/watch?v=ThVe4xvNZwI
- Example img URL: http://img.youtube.com/vi/ThVe4xvNZwI/0.jpg
- Pieces and Purpose

  img : substituted for www

  youtube.com : domain

  vi : indicated "video image"

  ThVe4xvNZwI : YouTube Name Code for specific video

  0 : image at time frame zero

  .jpg : file extension for this image

Full YouTube Exemplar
```html
<a href="https://www.youtube.com/watch?time_continue=0&v=ThVe4xvNZwI"
   target="_blank">
<img src="http://img.youtube.com/vi/ThVe4xvNZwI/0.jpg"
     alt="Cyber Defence Security Promo Video 2018"
     width="240"
     height="180"
     border="10" />
</a>
```

### GitHub Video Additions or Pure Markdown ###
Example HTML Tag Markdown
```html
<a href="Full-URL"
   target="_blank">
<p>You must click this hyperlink and Download the Video by clicking the "View Raw" to see it.</p>
</a>
```

Example in pure Markdown
```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```

### Image Transformations ###
Gathering images
- Use PrtSc (Print Screen) and Google Draw to save .jpg, then make it web sized
- Remember to set width and height
- Remember to set file size, Kb not Mb

Note: both URL Examples do not change save files, last checked

Ex #1: http://webresizer.com/

Ex #2: http://resizeimage.net/

Purpose of Image Transformations
- Resizes Images for viewing on webpage
- decreases sizes for saving
- able to save image to Google DOCs for display on webpage

Inline Reference Example
```
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")
```

Variable-type Reference
```
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

---

### To Do List ###

Example **To Do List**
- [] incomplete item
- [x] complete item
- [] <del>deleted item with HTML cross out tags</del>
- [] any unordered or ordered list syntax is supported

Note: HTML Cross out tags
```html
<del>brainstorming but not even tried</del>
```

---

### Hyperlinks and Texts

CATUION: opening the Hyperlink in a new Tab not currently support with attribute `target="_blank"`

1. Simple Hyperlink and Click Here Text, inline

`<a href="FULL URL">Click Here</a>`

2. Simple Hyperlink and Click Here, next line

`<a href="FULL URL"><p>Click Here</p></a>`

   - notice `<p></p>` automatically add `<br>` or line break tag

---

## Appendix ##
### Full URLs included above, accessed 20180714 ###
https://www.w3schools.com/htmL/

https://guides.github.com/features/mastering-markdown/

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
