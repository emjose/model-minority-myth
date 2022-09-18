<p id="header"><p>

<table><tr>
<td> <a href="https://github.com/emjose/mousetrail-wandavision/#header"><img src="https://res.cloudinary.com/dn1e07eul/image/upload/v1659330996/Readme%20Headers/header-left_ctkix5.png" alt="previous" style="width: 200px;"/></a> </td>
<td> <a href="https://github.com/emjose/one-hundred/#header"><img src="https://res.cloudinary.com/dn1e07eul/image/upload/v1659330606/Readme%20Headers/header-center_bkbdbt.png" alt="100 days of code" style="width: 580px;"/></a> </td>
<td> <a href="https://github.com/emjose/news-site/#header"><img src="https://res.cloudinary.com/dn1e07eul/image/upload/v1659330646/Readme%20Headers/header-right_eftaz9.png" alt="next" style="width: 200px;"/></a> </td>
</tr></table>

<br>

<p id="project-title"><p>

<a href=#table-of-contents>![Model Minority Myth](https://res.cloudinary.com/dn1e07eul/image/upload/v1659385855/Readme%20Headers/inter-026-model-minority-myth_gkzpqi.png)</a>

<br>

<a href="https://emjose.github.io/model-minority-myth/">![Model Minority Myth](Assets/preview-026-model-minority-myth.png)</a>

#

<p id="table-of-contents"><p>

<a href=#table-of-contents>![Table of Contents](https://res.cloudinary.com/dn1e07eul/image/upload/v1659241355/Readme%20Headers/inter-toc_euxbbw.png)</a>

-   [100 Days of Code](#100days)
-   [Installation](#installation)
-   [Issues](#issues)
-   [Live Site](#live-site)
-   [Resources](#resources)
-   [Copyright](#copyright)
-   [Say Hello](#say-hello)

<br>

#

<p id="100days"><p>

<a href=#100days>![#100DaysOfCode](https://res.cloudinary.com/dn1e07eul/image/upload/v1659389776/Readme%20Headers/inter-100hash_kjpgmt.png)</a>

### Day 26: April 5, 2021

-   During the Covid-19 pandemic, <a href="https://www.pewresearch.org/social-trends/2020/07/01/many-black-and-asian-americans-say-they-have-experienced-discrimination-amid-the-covid-19-outbreak/">there has been a marked increase in anti-Asian sentiment and racism in the United States.</a>

-   On March 16th, 2021, a mass shooting occured in three Atlanta spas and massage parlors. Eight people were killed, six of whom were Asian women.

-   As an Asian and a Filipino-American, I've been at a loss for words with current events. As a way of beginning to articulate my thoughts, I worked on this mini project with a scratch effect revealing the myth of the **<a href="https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth">"model minority."</a>**

-   The **<a href="https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth">"model minority" myth</a>** is the "one-size-fits-all" and stereotypical perception of Asians being a "polite, law-abiding group who have achieved a higher level of success than the general population through some combination of innate talent and pull-yourselves-up-by-your-bootstraps immigrant striving." Source: <a href="https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth">Learning for Justice.</a>

<br>

#

<p id="installation"><p>

<a href=#installation>![Installation](https://res.cloudinary.com/dn1e07eul/image/upload/v1659389842/Readme%20Headers/inter-installation_j9ixlq.png)</a>

#### 1. Git clone and cd into the repo folder:

```console
git clone git@github.com:emjose/model-minority-myth.git && cd model-minority-myth
```

#### 2. Run the command:

```console
open index.html
```

#### 3. On your device, move the cursor around to see the reveal effect.

<br>

#

<p id="issues"><p>

<a href=#issues>![Issues](https://res.cloudinary.com/dn1e07eul/image/upload/v1659392574/Readme%20Headers/inter-issues_mzq4o7.png)</a>

#### In the `script.js` file:

```javascript
const bubbles = document.createElement("span");
bubbles.style.left = -75 + e.offsetX + "px";
bubbles.style.top = -75 + e.offsetY + "px";
body.appendChild(bubbles);
```

-   The JavaScript function for the mousemove event creates a span element.

-   For the span to exceed the browser's frame, offset values are added to the mouse coordinates.
    <br>

<a href="https://emjose.github.io/model-minority-myth/">![Live Site](Assets/026-myth-2.gif)</a>

-   Due to the offset in pixel values, the span can appeared warped or rippled.

-   This warping is most apparent at the bottom of the browser frame.

<br>

#

<p id="live-site"><p>

<a href="https://emjose.github.io/model-minority-myth/">![Live Site](https://res.cloudinary.com/dn1e07eul/image/upload/v1659389947/Readme%20Headers/inter-live-site_ngkqcf.png)</a>

<a href="https://emjose.github.io/model-minority-myth/">![Live Site](Assets/026-myth.gif)</a>

• **[Model Minority Myth](https://emjose.github.io/model-minority-myth/)** is best viewed on a desktop or laptop computer browser.

• **[Model Minority Myth](https://emjose.github.io/model-minority-myth/)** is a [progressive web app](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps).

<br>

#

<p id="resources"><p>

<a href=#resources>![Resources](https://res.cloudinary.com/dn1e07eul/image/upload/v1659314247/Readme%20Headers/inter-resources_ncevbw.png)</a>

-   #### [Stop AAPI Hate](https://stopaapihate.org/)

-   #### [Unsplash Images](https://unsplash.com/)

-   #### [Anti-Asian Violence Resources](https://anti-asianviolenceresources.carrd.co/)

-   #### [What is the Model Minority Myth?](https://www.learningforjustice.org/magazine/what-is-the-model-minority-myth)

-   #### [Stop Asian Hate: GoFundMe Organizations](https://www.gofundme.com/c/act/stop-aapi-hate)

-   #### ["Not Your Model Minority" poem by Rosa Kim](https://bclawimpact.org/2021/02/15/not-your-model-minority/)

-   #### [Scratch Effect Tutorial](https://youtu.be/qzcMiNKPSIk) by [Online Tutorials](https://www.youtube.com/channel/UCbwXnUipZsLfUckBPsC7Jog)

-   #### [The text was created with Adobe Photoshop](https://www.adobe.com/products/photoshop.html)

-   #### [My blog on how I created my Github READMEs](https://emmanueljose.medium.com/readme-a-makeover-story-b9c7be37a6de?sk=7ae6623d365409d875753e4604e42ffd)

<br>

#

<p id="copyright"><p>

<a href=#copyright>![Copyright](https://res.cloudinary.com/dn1e07eul/image/upload/v1659391383/Readme%20Headers/inter-copyright_ax53yz.png)</a>

-   Special thank you to [Kimson Doan](https://unsplash.com/photos/HD8KlyWRYYM) for her photo on [Unsplash](https://unsplash.com/).

-   Photo copyright of © <a href="https://unsplash.com/@kimsondoan">Kimson Doan</a>. All Rights Reserved.

<br>

#

<p id="say-hello"><p>

<a href=#say-hello>![Say Hello](https://res.cloudinary.com/dn1e07eul/image/upload/v1659392702/Readme%20Headers/inter-say-hello_ccx3yf.png)</a>

<p><a href="https://twitter.com/Emmanuel_Labor"><img src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" height=30 width=90 alt="Twitter badge"></a> <a href="https://www.linkedin.com/in/emmanuelpjose/"><img src="https://img.shields.io/badge/linkedin-%230064e7.svg?&style=for-the-badge&logo=linkedin&logoColor=white" height=30 width=90 alt="Linkedin badge"></a> <a href="https://emmanueljose.medium.com/"><img src="https://img.shields.io/badge/medium-%238700f5.svg?&style=for-the-badge&logo=medium&logoColor=white" height=30 width=90 alt="Medium badge"></a> <a href="https://www.instagram.com/emmanuel_jose/"><img src="https://img.shields.io/badge/instagram-%23ff0077.svg?&style=for-the-badge&logo=instagram&logoColor=white" height=30 width=90 alt="Instagram badge"></a> <a href="mailto:emjose@gmail.com"><img src="https://img.shields.io/badge/gmail-%23fd1745.svg?&style=for-the-badge&logo=gmail&logoColor=white" height=30 width=90 alt="Gmail badge"></a> <a href="https://www.emmanuel-jose.com/"><img src="https://img.shields.io/badge/portfolio-%23FF0000.svg?&style=for-the-badge&logoColor=white" height=30 width=90 alt="Portfolio badge"></a> <a href="https://github.com/emjose"><img src="https://img.shields.io/badge/github-%23ff8e44.svg?&style=for-the-badge&logo=github&logoColor=white" height=30 width=90 alt="Github badge"></a></p>

#

<a href=#header>![Back to Top](https://res.cloudinary.com/dn1e07eul/image/upload/v1659314270/Readme%20Headers/inter-back-to-top_cubvxj.png)</a>
