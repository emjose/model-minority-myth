<p id="header"><p>

<table><tr>
<td> <a href="https://github.com/emjose/mousetrail-wandavision/#header"><img src="Assets/header-left.png" alt="previous" style="width: 200px;"/></a> </td>
<td> <a href="https://github.com/emjose/one-hundred/#header"><img src="Assets/header-center.png" alt="100 days of code" style="width: 580px;"/></a> </td>
<td> <a href=#header><img src="Assets/header-right-g.png" alt="next" style="width: 200px;"/></a> </td>
</tr></table>


<!-- <a href="https://github.com/emjose/***next-repo***/#header"><img src="Assets/header-right.png" alt="next" style="width: 200px;"/></a> -->

<br>

<p id="project-title"><p>

<a href=#table-of-contents>![Model Minority Myth](Assets/inter-026-model-minority-myth.png)</a> 

<br>

<a href="https://emjose.github.io/model-minority-myth/">![Model Minority Myth](Assets/preview-026-model-minority-myth.png)</a> 

#

<p id="table-of-contents"><p>

<a href=#table-of-contents>![Table of Contents](Assets/inter-toc.png)</a>  

- [100 Days of Code](#100days)
- [Installation](#installation) 
- [Issues](#issues)
- [Live Site](#live-site)
- [Resources](#resources)
- [Let's Connect!](#lets-connect) 

#

<p id="100days"><p>

<a href=#100days>![#100DaysOfCode](Assets/inter-100hash.png)</a>  

### Day 26: April 6, 2021
- During the Covid-19 pandemic, <a href="https://www.pewresearch.org/social-trends/2020/07/01/many-black-and-asian-americans-say-they-have-experienced-discrimination-amid-the-covid-19-outbreak/">there has been a marked increase in anti-Asian sentiment and racism in the United States.</a> 
  
- On March 16th, 2021, a mass shooting occured in three Atlanta spas and massage parlors. Eight people were killed, six of whom were Asian women.
  
- As an Asian and a Filipino-American, I've been at a loss for words with current events. As a way of beginning to articulate my thoughts, I worked on this mini project with a scratch effect revealing the myth of the **<a href="https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth">"model minority."</a>**
  
- The **<a href="https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth">"model minority" myth</a>** is the stereotypical perception of Asians being a "polite, law-abiding group who have achieved a higher level of success than the general population through some combination of innate talent and pull-yourselves-up-by-your-bootstraps immigrant striving." Source: <a href="https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth">Learning for Justice.</a>

#

<p id="installation"><p>

<a href=#installation>![Installation](Assets/inter-installation.png)</a>

#### Git clone and cd into the repo folder:
``` 
git clone git@github.com:emjose/model-minority-myth.git && cd model-minority-myth 
```
#### Run the command:
```
open index.html
```

#

<p id="issues"><p>

<a href=#issues>![Issues](Assets/inter-issues.png)</a>

- The JavaScript function for the mousemove event creates a span element. 
  
- For the span element to exceed the padding of the browser frame, offset values are required.
```
    const bubbles = document.createElement('span');
    bubbles.style.left = -75 + e.offsetX + 'px';
    bubbles.style.top = -75 + e.offsetY + 'px';
    body.appendChild(bubbles);
```
- Due to the offset in pixel values, the span can appeared warped or rippled. 
  
- This warping is most apparent at the bottom of the browser frame.
<!-- <a href="https://emjose.github.io/model-minority-myth/">![Live Site](Assets/issue-example.png)</a> -->
<a href="https://emjose.github.io/model-minority-myth/">![Live Site](Assets/026-myth-2.gif)</a>

#

<p id="live-site"><p>

<a href="https://emjose.github.io/model-minority-myth/">![Live Site](Assets/inter-live-site.png)</a>

<a href="https://emjose.github.io/model-minority-myth/">![Live Site](Assets/026-myth-1.gif)</a>

#

<p id="resources"><p>

<a href=#resources>![Resources](Assets/inter-resources.png)</a>  

- #### [Stop AAPI Hate](https://stopaapihate.org/)
  
- #### [Anti-Asian Violence Resources](https://anti-asianviolenceresources.carrd.co/)

- #### [What is the Model Minority Myth?](https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth)

- #### [Stop Asian Hate: GoFundMe Organizations](https://www.gofundme.com/c/act/stop-aapi-hate) 

- #### ["Not Your Model Minority" poem by Rosa Kim](https://bclawimpact.org/2021/02/15/not-your-model-minority/)

- #### [Thank you to Kimson Doan](https://unsplash.com/photos/HD8KlyWRYYM) for her photo on [Unsplash](https://unsplash.com/)

- #### [My blog on how I created my Github READMEs](https://emmanueljose.medium.com/readme-a-makeover-story-b9c7be37a6de?sk=7ae6623d365409d875753e4604e42ffd) 

#

<p id="lets-connect"><p>

<a href=#lets-connect>![Say Hello](Assets/inter-say-hello.png)</a>

<p><a href="https://twitter.com/Emmanuel_Labor"><img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" height=30 width=90 alt="Twitter badge"> <a href="https://www.linkedin.com/in/emmanuelpjose/"><img src="https://img.shields.io/badge/linkedin-%230064e7.svg?&style=for-the-badge&logo=linkedin&logoColor=white" height=30 width=90 alt="Linkedin badge"> <a href="https://emmanueljose.medium.com/"><img src="https://img.shields.io/badge/medium-%238700f5.svg?&style=for-the-badge&logo=medium&logoColor=white" height=30 width=90 alt="Medium badge"> <a href="https://www.instagram.com/emmanuel_jose/"><img src="https://img.shields.io/badge/instagram-%23ff0077.svg?&style=for-the-badge&logo=instagram&logoColor=white" height=30 width=90 alt="Instagram badge"> <a href="mailto:emjose@gmail.com"><img src="https://img.shields.io/badge/gmail-%23fd1745.svg?&style=for-the-badge&logo=gmail&logoColor=white" height=30 width=90 alt="Gmail badge"> <a href="https://www.youtube.com/channel/UCQdqFg-_J83jn9xJRd1W3tQ/videos"><img src="https://img.shields.io/badge/youtube-%23FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white" height=30 width=90 alt="Youtube badge"> <a href="https://github.com/emjose"><img src="https://img.shields.io/badge/github-%23ff8e44.svg?&style=for-the-badge&logo=github&logoColor=white" height=30 width=90 alt="Youtube badge"></p>

#

<a href=#header>![Back to Top](Assets/inter-congrats.png)</a> 