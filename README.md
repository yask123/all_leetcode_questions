# All Leetcode questions in a single file


I wanted to practice Leetcode questions with pen and paper on my Kindle. 
So, I wrote a script which copies all Leetcode algorithmic questions and formats it in a single file (txt, pdf, mobi) .

<img height="50%" width="50%" src= "https://pbs.twimg.com/media/C8bVGM-U0AA8ogx.jpg"/>


### Usage

You can  download '.txt', '.pdf' or '.mobi' file from this repo and view it however you want. 

### Updating questions

Add the new question link in the file `question_links.txt` and run `export_all_questions.py` python script. 

To get all questions link list, visit this URL 'https://leetcode.com/problemset/algorithms/', open up the dev console and run following code:


```
var links = document.getElementsByTagName('a');
var all_links =  Array.prototype.slice.call(links);
all_links.forEach(function(val){
    console.log(val.href);
});
```
