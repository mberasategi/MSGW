---
title: UNIT 2<br />Writing for the web
subtitle: BASIC principles for writing for the web
theme: deusto
deusto: TRUE
revealjs-url: ../reveal.js
template: ../reveal.js/default.revealjs
css: style.css
...

# How we read online

## 

<div style="height:3em;">&nbsp;</div>

>On the average Web page, users have time to read at most 28% of the words during an average visit; 20% is more likely.

<figure style="text-align:right;">
    <figcaption>Jakob Nielsen (2008), ["How Little Do Users Read?"](https://www.nngroup.com/articles/how-little-do-users-read/)</figcaption>
</figure> 

## 

<div style="height:1em;">&nbsp;</div>

![Page visit time per word count](img/page-visit-time-per-word-count.gif)

::: notes
Obviously, users tend to spend more time on pages with more information. However, the best-fit formula tells us that they spend only 4.4 seconds more for each additional 100 words.

Usually, I assume a reading speed of 200 words per minute (WPM), but because the users in this study are highly literate, I'll go with 250 WPM. At that reading speed, users can read 18 words in 4.4 seconds. Thus, when you add verbiage to a page, you can assume that customers will read 18% of it.

The formula in the chart above indicates that there is a fixed time of about 25 seconds, plus an additional 4.4 seconds per 100 words.
:::

## 

<div style="height:1em;">&nbsp;</div>

![Our reading is dynamic: multiple sources at the same time, in search for speed, often non-linear reading](img/remove-online-distractions.jpg)

## 

![Reading on a screen is tiresome](img/860_blue_light_and_sleep.png){title="&copy; Junpinzon/iStockPhoto"}

::: notes

- Screen text is read 25% slower than print text
- regardless of technological advances, resolution/blue light still makes it tiresome
- scrolling is annoying

:::


# Highlights

## B is for brevity {data-transition="slide-in fade-out"}

- We tend to read less on screen that we did on paper. Less so on mobile.
    + The custom of writing with brevity remains, although
    + recent research challenges this.

## B is for brevity {data-transition="fade"}

<!-- > The place between 500 and 800 words is the place you don't want to be because it's not short and fast and focused and shareable, but it's not long enough to be a real pay-off for readers.  -->

<div class="small">
Readers prefer:

- Short, sharp, creative takes on news stories that say something new, OR
- long, in-depth articles providing strong detailed narrative or insightful analysis.
</div>
**What they _don't_ like is the stuff in the middle** &mdash; 500 to 800 word articles that provide exhaustive detail but no insight.

<figure style="text-align:right;"><figcaption>Jasper Jackson (2013), Is this article too long or too short? Why newspapers are writing the wrong articles for the web [[archived version](https://web.archive.org/web/20160306010246/http://www.themediabriefing.com/article/is-this-article-too-long-why-newspapers-are-getting-their-article-length-just-wrong-for-the-web)] </figcaption></figure>

## B is for brevity {data-transition="fade" .small}

- **Full length of article**. Either longform (+1,500w ~ 7min read) or short (around 300w)
- **Length of sentences/paragraps**. One concept per paragraph
- **Characters per line**. Fewer characters per line makes the text appear less complex

<div class="fragment fade-in" data-fragment-index="1">
<div class="fragment fade-out" data-fragment-index="2">

![By adding a featured image (or something else) <br />side by side with the first paragraph](img/short-line-1.png){width="500"}

</div>
</div>

<div class="fragment" data-fragment-index="2" style="margin-top:-325px;">
![By increasing font size on the first paragraph](img/short-line-2.png){width="500"}
</div>

## B is for brevity {data-transition="fade" .small}

- **Full length of article**. Either longform (+1,500w ~ 7min read) or short (around 300w)
- **Length of sentences/paragraps**. One concept per paragraph
- **Characters per line**. Fewer characters per line makes the text appear less complex
- **'Chunk' a larger piece into shorter parts**. Each should have a particular focus. Pagination:<div class="smaller">
    - increases entry points
    - no need of vertical scroll
    - shorter text more appealing
    - nonlinear reading, guided by interest</div>

## B is for brevity {data-transition="fade-in slide-out" .small}

<div style="font-family:sans-serif;padding:.3em .6em; border-radius:7px; background-color:#ebcb8b;text-align:center;margin:0 auto;width:70%">

<div style="width:100px;margin:.25em auto;">
<svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="exclamation-triangle" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" class="svg-inline--fa fa-exclamation-triangle fa-w-18 fa-2x"><path fill="currentColor" d="M569.517 440.013C587.975 472.007 564.806 512 527.94 512H48.054c-36.937 0-59.999-40.055-41.577-71.987L246.423 23.985c18.467-32.009 64.72-31.951 83.154 0l239.94 416.028zM288 354c-25.405 0-46 20.595-46 46s20.595 46 46 46 46-20.595 46-46-20.595-46-46-46zm-43.673-165.346l7.418 136c.347 6.364 5.609 11.346 11.982 11.346h48.546c6.373 0 11.635-4.982 11.982-11.346l7.418-136c.375-6.874-5.098-12.654-11.982-12.654h-63.383c-6.884 0-12.356 5.78-11.981 12.654z" class=""></path></svg>
</div>

<div style="font-family:raustila, sans-serif;font-size:60px;">pagination</div>

<div class="small">

<strike>"as we said before"</strike>

repeat basic information

split based on meaning, not length

significant connection to other fragments
</div></div>

::: notes

- we should not assume the user has read other pages. provide background info and/or links instead
- repeating basic information may be required to compensate for loss of context: fragment needs to be self-explaining without any more context
- do not paginate based on lenght only ("continue" button at the bottom)
- fragments need to be significantly inter-connected
 
:::


## A is for adaptability {data-transition="slide-in fade-out"}

- The journalist needs to be able to adapt the story to the best medium available (types of reporting, media, platforms). Minimum media literacy is required
- The journalist needs to think about how the content itself might be adapted by users: allow embedding or downloading, enable sharing &darr;

## A is for adaptability {data-transition="fade-in slide-out"}

![Social media buttons can be placed at the top, bottom, right or left of the post, or inline the text](img/sharebutton.png){width="350"}

>People love to share quotes on social media. Make your perfect blog post as quotable and shareable as possible.

<figure style="text-align:right;"><figcaption>Kevan Lee (2015), <a href="https://buffer.com/resources/perfect-blog-post-research-data" target="_blank">The Anatomy of a Perfect Blog Post: The Data on <br />Headlines, Length, Images and More</a></figcaption></figure>

## 

<div style="margin-top:-75px;">
![Tim Soulo, [The Anatomy of a Tweetable Quote](https://bloggerjet.com/create-tweetable-quotes/)](img/tweetable-quote.jpg)
</div>

## S is for scannability {data-transition="slide-in fade-out"}

Especially with longer content, it is important to enable users to scan the page without having to read it completely. 

<!-- >The ultimate effect is to draw your eye down the page and engage you for longer. Just as a good text article used to mix quotes with facts and backgrounds, a good online article does all that _and_ mixes in images, tweets or video. <span class="sans">(p.81)</span> -->

<div class="box center" style="border-radius:.3em">
<h4 style="color:#333;padding-top:.6em">80/20 rule</h4>
80% of the people will read 20% of the content. 
</div>

## S is for scannability {data-transition="fade"}

Clear, unambiguous <span class="highlighted">headlines and subheadings</span>, with a focus on the first (and last) two or three words in the headline, intro and subheadings &mdash; we don't just scan body text, we scan headlines, too.

![In terms of SEO, the headline should also aim to be <br />around 55 characters or less ([Lee 2015](https://buffer.com/resources/perfect-blog-post-research-data))](img/seo-headlines.png){width=600}

## S is for scannability {data-transition="fade"}

Headline strategies backed by psychology ([Lee 2015](https://buffer.com/resources/perfect-blog-post-research-data)): 

<div class="smaller">
- Surprise – “This Is Not a Perfect Blog Post (But It Could’ve Been)”
- Questions – “Do You Know How to Create the Perfect Blog Post?”
- Curiosity gap – “10 Ingredients in a Perfect Blog Post. Number 9 Is Impossible!”
- Negatives – “Never Write a Boring Blog Post Again”
- How to – “How to Create a Perfect Blog Post”
- Numbers – “10 Tips to Creating a Perfect Blog Post”
- Audience referencing – “For People on the Verge of Writing the Perfect Blog Post”
- Specificity – “The 6-Part Process to Getting Twice the Traffic to Your Blog Post”
</div>

::: notes

Activity: transform headlines from individual submissions (or try to find others ti give them) using the strategies.

:::

## S is for scannability {data-transition="fade"}

<span class="highlighted">Subheadings</span> are the heading tags that appear inside your post editor. 

- `H1`: post/page title
- `H2`s and `H3`s: subheadings and sub-subheadings
- `H4`: name of the site, widget titles
- `H5`: same as above, sidebars, etc.

## S is for scannability {data-transition="fade"}

A clear <span class="highlighted">summary</span> that tells the story quickly.

- the inverted pyramid
- avoid 'setting the scene' unless it's a longform piece (in which case, storytelling &mdash;starting with a personal anecdote or a moment of transpareny&mdash; is recommended)

## S is for scannability {data-transition="fade"}

![Jakob Nielsen (1996), ["Inverted Pyramids in Cyberspace"](https://www.nngroup.com/articles/inverted-pyramids-in-cyberspace/)
<br />Amy Schade (2018), ["Inverted Pyramid: Writing for Comprehension"](https://www.nngroup.com/articles/inverted-pyramid/)
](img/inverted-pyramid.png){width="600"}


::: notes

<div class="smallest" style="font-size:.6em !important;">

- traditional pyramid: intro > details > conclusion
- inverted comes from the field of journalism:
    - start the article by telling the reader the conclusion, follow by the most important supporting information, and end by giving the background.
    - useful for newspapers because **readers can stop at any time** and will still get the most important parts of the article.
- even more important on the web because users barely scroll - important things should go _above the fold_
- **the Web is a linking medium** and we know from hypertext theory that writing for interlinked information spaces is different than writing linear flows of text --  no need for so much background
    + _rhetoric of departure_ and _rhetoric of arrival_ to indicate the need for both ends of the link to give users some understanding of where they can go as well as why the arrival page is of relevance to them.
- how to:
    + identify key points
    + rank secondary information
    + write well and concisely
    + frontload all elements of content with important information
    + consider adding a summary or list of highlights
- the fold: We don’t go to a page, see useless and irrelevant content, and scroll out of the blind hope that something useful may be hidden 5 screens down.

</div>

:::

## S is for scannability {data-transition="fade"}

![Amy Schade (2015), ["The Fold Manifesto: Why the Page Fold Still Matters"](https://www.nngroup.com/articles/page-fold-manifesto/)](img/inverted-pyramid-fold.png){width="600"}

::: notes
- What appears at the top of the page vs. what’s hidden will always influence the user experience — regardless of screen size. The average difference in how users treat info above vs. below the fold is 84%.
:::

## S is for scannability {data-transition="fade"}

<span class="highlighted">Links</span> are the ultimate building blocks of the hypertextual web, and they also serve as CTAs (calls to action: _click me!_) and scannable elements. An estimated avg of 10 links per post (in a study cited in [Lee 2015](https://buffer.com/resources/perfect-blog-post-research-data)).

<div class="sans small center">

<div style="color:#bf616a;" class="fragment"> 
**&times;** <a href="" style="text-decoration:underline;color:#bf616a;">click here</a>
</div>

<div style="color:#bf616a;" class="fragment"> 
**&times;** <a href="" style="text-decoration:underline;color:#bf616a;">You can find the assignment description on the ALUD platform</a>
</div>

<span class="fragment">You can find <a href="" style="text-decoration:underline;color:#666;">the assignment description</a> on the ALUD platform</span>  
<span class="fragment">You can find the assignment description <a href="" style="text-decoration:underline;color:#666;">on the ALUD platform</a></span>  
<span class="fragment">You can find <a href="" style="text-decoration:underline;color:#666;">the assignment description</a> on <a href="" style="text-decoration:underline;color:#666;">the ALUD platform</a></span>
</div>

::: notes

click here: it doesn't matter what sits either site of those two words 'click here to read', 'to find out more click here' because it will not be read. 

A link should make sense on its own, out of context.

Should always deep link when possible (not link to the homepage). If you are linking to anything other than a webpage, it should be made clear (PDF, spreadsheets, documents...)

:::


## S is for scannability {data-transition="fade-in slide-out"}

Other elements for scannability:

- bullet or numbered lists
- indented quotes
- numbers
- highlighted words or sentences
- breaking up the text (avg of one visual every 350 words) with images, galleries, charts, video maps... or
- embedded material (tweets, videos, presentations), instead of simply linked

## I is for interactivity

>What might a user want to do while their read your article? <span class="sans">(p.82)</span>

Enable this through:

- shareable quotes/pictures
- embedded media
- links
- other interactive technologies

## C is for community/conversation {.small}

>Good journalism has always sought to serve a community, [...] and good journalism &ndash; whether informative or sensationalist &ndash; has always generated conversation. <span class="sans">(p.82)</span>

<!-- <div class="box center" style="margin-top:1.2em;padding-top:.6em;font-size:1.2em">
</div> -->
#### <strike>content</strike>conversation is king

- _comment_ on blogs, post on forums, update wikis, converse in social media
- _link_ to sources
- _listen_, follow, monitor (and start over: respond, comment, link, open up)