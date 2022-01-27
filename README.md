# docsTest
Testing a documentation site

This is a quick prototype of a docs site. You're currently located on the front page of `https://johncschuster.github.io/docsTest/`. The content is served using [GitHub Pages](https://pages.github.com/) and the front-end is [GatsbyJS](https://www.gatsbyjs.com/)

The repo itself for the content can be found here: 
[`https://github.com/johncschuster/docsTest`](https://github.com/johncschuster/docsTest)


### How are you storing and serving images like that sweet headshot below?

Well, dear reader, I'm glad you asked.

Images can be stored in the repo itself, and we can embed them in these articles using their relative paths; very handy for the inevitable move to NewDot.

For example, the headshot below is stored in the folder `/assets/images/`. 

![filePathDemo](/assets/images/filePath.png)

That makes the relative path of the file `/assets/images/2017_John_Schuster.jpg`. Using `![alt text for image](/assets/images/filename.jpg)` we can embed the image right in the article like so! ⬇️


![/assets/images/2017_John_Schuster.jpg](/assets/images/2017_John_Schuster.jpg)

