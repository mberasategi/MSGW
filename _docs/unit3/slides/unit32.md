---
title: UNIT 3<br />Writing for the web
subtitle: 3.2 Search Engine Optimization (SEO)
theme: deusto
deusto: TRUE
revealjs-url: ../../../assets/reveal.js
css: style.css
...

## Definition 

### What is SEO?

>SEO stands for “search engine optimization.” It’s the practice of increasing both the quality and quantity of website traffic, as well as exposure to your brand, through non-paid (also known as "organic") search engine results.

<figure style="text-align:right;">
    <figcaption>SeoMOZ, "[Chapter 1. SEO 101](https://moz.com/beginners-guide-to-seo/why-search-engine-marketing-is-necessary)" from [_The Beginner's Guide to SEO_](https://moz.com/beginners-guide-to-seo)</figcaption>
</figure> 

### Search engines 

Optimization of content for search engines, but reaching people is the ultimate objective.

<div class="box center fragment" data-fragment-index="1" style="margin-bottom:1em;">

<div style="font-family:raustila,sans-serif;font-size:1.2em;color:#666;float:left;transform: rotate(-20deg);padding-top:.3em;">Key term</div> 

**S**earch **E**ngine **R**esults **P**age (SERP)

</div>


<table class="fragment" data-fragment-index="2"><tr><td style="width:30%;" class="right">

search query <div style="width:20px;display:inline-block;"><svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-alt-right" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="svg-inline--fa fa-arrow-alt-right fa-w-14 fa-2x"><path fill="currentColor" d="M0 304v-96c0-13.3 10.7-24 24-24h200V80.2c0-21.4 25.8-32.1 41-17L441 239c9.4 9.4 9.4 24.6 0 34L265 448.7c-15.1 15.1-41 4.4-41-17V328H24c-13.3 0-24-10.7-24-24z" class=""></path></svg></div>

</td><td style="width:40%;">

<div class="box center" style="background-color:black;color:white;padding-top:.6em;">
<div style="width:50px;display:inline-block;"><svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="function" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" class="svg-inline--fa fa-function fa-w-20 fa-2x"><path fill="currentColor" d="M288.73 320c0-52.34 16.96-103.22 48.01-144.95 5.17-6.94 4.45-16.54-2.15-22.14l-24.69-20.98c-7-5.95-17.83-5.09-23.38 2.23C246.09 187.42 224 252.78 224 320c0 67.23 22.09 132.59 62.52 185.84 5.56 7.32 16.38 8.18 23.38 2.23l24.69-20.99c6.59-5.61 7.31-15.2 2.15-22.14-31.06-41.71-48.01-92.6-48.01-144.94zM224 16c0-8.84-7.16-16-16-16h-48C102.56 0 56 46.56 56 104v64H16c-8.84 0-16 7.16-16 16v48c0 8.84 7.16 16 16 16h40v128c0 13.2-10.8 24-24 24H16c-8.84 0-16 7.16-16 16v48c0 8.84 7.16 16 16 16h16c57.44 0 104-46.56 104-104V248h40c8.84 0 16-7.16 16-16v-48c0-8.84-7.16-16-16-16h-40v-64c0-13.2 10.8-24 24-24h48c8.84 0 16-7.16 16-16V16zm353.48 118.16c-5.56-7.32-16.38-8.18-23.38-2.23l-24.69 20.98c-6.59 5.61-7.31 15.2-2.15 22.14 31.05 41.71 48.01 92.61 48.01 144.95 0 52.34-16.96 103.23-48.01 144.95-5.17 6.94-4.45 16.54 2.15 22.14l24.69 20.99c7 5.95 17.83 5.09 23.38-2.23C617.91 452.57 640 387.22 640 320c0-67.23-22.09-132.59-62.52-185.84zm-54.17 231.9L477.25 320l46.06-46.06c6.25-6.25 6.25-16.38 0-22.63l-22.62-22.62c-6.25-6.25-16.38-6.25-22.63 0L432 274.75l-46.06-46.06c-6.25-6.25-16.38-6.25-22.63 0l-22.62 22.62c-6.25 6.25-6.25 16.38 0 22.63L386.75 320l-46.06 46.06c-6.25 6.25-6.25 16.38 0 22.63l22.62 22.62c6.25 6.25 16.38 6.25 22.63 0L432 365.25l46.06 46.06c6.25 6.25 16.38 6.25 22.63 0l22.62-22.62c6.25-6.25 6.25-16.38 0-22.63z" class=""></path></svg></div>

<p style="margin-top:0;">The Algorithm</p>
</div>

</td><td style="width:30%;">

<div style="width:20px;display:inline-block;"><svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-alt-right" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="svg-inline--fa fa-arrow-alt-right fa-w-14 fa-2x"><path fill="currentColor" d="M0 304v-96c0-13.3 10.7-24 24-24h200V80.2c0-21.4 25.8-32.1 41-17L441 239c9.4 9.4 9.4 24.6 0 34L265 448.7c-15.1 15.1-41 4.4-41-17V328H24c-13.3 0-24-10.7-24-24z" class=""></path></svg></div>  <p style="display:inline-block">SERP</p>

</td></tr></table>

<figure class="fragment" data-fragment-index="2"><figcaption>Search engines work with what could be considered a _black box model_</figcaption></figure>

### Organic search results

![](img/organic.jpg){class="right" width="400"}

Not paid for \(_vs._ advertising).

Respond to the search query, ordered by relevance according to the algorithm.

Considered to be the _natural_ results of search, not interfered by anything else.

This is what SEO is about; trying to get ranked higher through the algorithm. 


### {data-background-image="img/organic-page.jpg" data-background-position="top"}

::: notes

used to be easily distinguishable from paid results

::: 

### SERP features

<div class="small" style="margin:1em 0;">
- **Paid Results** that are bought by bidding on keywords  
  (e.g., AdWords or Google Shopping)
- **Rich Snippets** which add a visual layer to an existing result  
  (e.g., review stars for product ratings)
- **Universal Results** that appear in addition to organic results  
  (e.g., image results, new results, featured snippets)
- **Knowledge Graph** data which appears as panels or boxes  
  (e.g., weather, Celebrity Knowledge Panel)
</div>

<figure class="right"><figcaption>SEOmoz, [What is a SERP feature?](https://moz.com/learn/seo/serp-features)</figcaption></figure>


::: notes

Not a traditional organic result 

:::

### SERP features

![What's the weather forecast for Donostia?](img/weather.png){width="400" style="border:solid 1px #ccc !important;"}

### How?

<div style="height:1em;"> </div>
Essentially:

> Don’t try to trick search engines. Instead, provide your visitors with a great online experience.

---

<h3> Basic principles <div style="width:60px;display:inline-block;margin-left:30px;color:#666"><svg aria-hidden="true" focusable="false" data-prefix="far" data-icon="hat-wizard" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="svg-inline--fa fa-hat-wizard fa-w-16 fa-2x"><path fill="currentColor" d="M496 464h-35.5l-81.32-200.17c-7.21-17.73-7.99-37.64-2.21-55.94L442.67 0 223.83 131.92c-27.61 16.64-49.46 42.15-62.37 72.8L52.22 464H16c-8.84 0-16 7.16-16 16v16c0 8.84 7.16 16 16 16h480c8.84 0 16-7.16 16-16v-16c0-8.84-7.16-16-16-16zm-256 0l10.67-21.33L304 416l-53.33-26.67L224 336l-26.67 53.33L144 416l53.33 26.67L208 464H104.31l101.38-240.64c.99-2.36 2.34-4.5 3.49-6.77L224 224l16 32 16-32 32-16-32-16-8.93-17.86c.53-.34 1-.79 1.54-1.11l110-66.31-27.4 86.71c-9.15 28.96-7.91 60.38 3.51 88.47l6.86 16.89L320 288l-16-32-16 32-32 16 32 16 16 32 16-32 25.09-12.55L408.69 464H240z" class=""></path></svg></div></h3>

>- Make pages primarily for **users, not search engines**.
>- Don't deceive your users.
>- **Avoid tricks** intended to improve search engine rankings. A good rule of thumb is whether you'd feel comfortable explaining what you've done to a website to a Google employee. Another useful test is to ask, "Does this help my users? Would I do this if search engines didn't exist?"
>- Think about what makes your website unique, valuable, or engaging.

---

<h3> Things to avoid <div style="width:60px;display:inline-block;margin-left:30px;color:#333"><svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="hat-witch" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" class="svg-inline--fa fa-hat-witch fa-w-18 fa-2x"><path fill="currentColor" d="M571.21 426.81l-22.66-22.66c-6.03-6.03-15.49-5.96-21.99-.43C492.89 432.38 450.6 448 405.89 448H170.11c-44.71 0-87.01-15.62-120.68-44.28-6.5-5.53-15.95-5.61-21.99.43L4.79 426.81c-6.44 6.44-6.45 17.25.4 23.25C50.85 490.12 108.8 512 170.11 512h235.78c61.31 0 119.26-21.88 164.93-61.94 6.84-6 6.84-16.81.39-23.25zM224 416v-64c0-17.67 14.33-32 32-32h64c17.67 0 32 14.33 32 32v64h53.89c23.94 0 46.54-5.79 67.29-15.91l-79.6-185.73a64.009 64.009 0 0 1-1.89-45.45l6.35-19.04A32.01 32.01 0 0 1 428.4 128h39.2c13.77 0 26 8.81 30.36 21.88L512 192l30.36-77.24c3.83-11.5.84-24.18-7.73-32.75L465.28 9.37c-10.21-10.2-25.97-12.32-38.5-5.16L260.43 107.18a128.004 128.004 0 0 0-53.47 59.15L103.03 400.19c20.69 10.06 43.23 15.81 67.08 15.81H224zm32 0h64v-64h-64v64z" class=""></path></svg></div></h3>

- Automatically generated content
- Participating in link schemes
- Creating pages with little or no original content (i.e. copied from somewhere else)
- Cloaking — the practice of showing search engine crawlers different content than visitors.
- Hidden text and links
- Doorway pages — pages created to rank well for specific searches to funnel traffic to your website.

::: notes

Link schemes: 

- Good - Create a link to a website you recommend for you visitors
- Bad - Create a link designed to increase your site's ranking or PageRank.

:::

### {data-background-image="img/seo-goals.jpg" data-background-position="top"}

<div style="margin-top:2em;background:rgba(255,255,255,.6);padding:.6em .3em">

<blockquote style="color:black;"><p>
Setting (and eventually achieving) <span class="highlighted">the right goals</span> is one of the most important things you can do as an SEO.
</p></blockquote>


<figure class="right"><figcaption>Rand Fishkin, ["How Do You Set Smart SEO Goals <br />for Your Team/Agency/Project?"](https://moz.com/blog/smart-seo-goals) at SEOmoz</figcaption></figure>

 </div>


## How search engines work

### 

Search engines have three primary functions:

1. **Crawl:** Scour the Internet for content, looking over the code/content for each URL they find.
1. **Index:** Store and organize the content found during the crawling process. Once a page is in the index, it’s in the running to be displayed as a result to relevant queries.
1. **Rank:** Provide the pieces of content that will best answer a searcher's query, which means that results are ordered by most relevant to least relevant. 

<!-- 
https://moz.com/beginners-guide-to-seo/how-search-engines-operate
-->

### 1. Crawl {data-transition="slide-in fade-out"}

![](img/crawling.svg)

::: notes

Crawling is the discovery process in which search engines send out a team of robots (known as crawlers or spiders) to find new and updated content. Content can vary — it could be a webpage, an image, a video, a PDF, etc. — but regardless of the format, content is discovered by links.

Googlebot starts out by fetching a few web pages, and then follows the links on those webpages to find new URLs. By hopping along this path of links, the crawler is able to find new content and add it to their index called Caffeine — a massive database of discovered URLs — to later be retrieved when a searcher is seeking information that the content on that URL is a good match for.

:::

### 1. Crawl {data-transition="fade"}

Search engines need to find our pages in order for them to appear as search results.

To check how many/which pages are indexed in a search engine, use the `site:` advanced operator:

<div class="box">

```
site:deusto.es
```

</div>

###  {data-transition="fade"}

![&nbsp;](img/crawl-results.png)

### 1. Crawl {data-transition="fade"}

Make sure the bot can crawl _through_ your website, and not just _to_ it.

>- Is content hidden behind login forms?
>- Are you relying on search forms (instead of navigation menus)?
>- Is text hidden within non-text content?
>- Can search engines follow your site navigation?

::: notes
- crawlers cannot log in, unable to access that content
- same
- text in images, videos, gifs; will not be understood / indexed / ranked well
- Just as a crawler needs to discover your site via links from other sites, it needs a path of links on your own site to guide it from page to page.
:::

### 1. Crawl {data-transition="fade"}

![&nbsp;](img/crawl-nav.svg)

::: notes

If you’ve got a page you want search engines to find but it isn’t linked to from any other pages, it’s as good as invisible

:::

### 1. Crawl {data-transition="fade-in slide-out"}

Make sure the bot can crawl _through_ your website, and not just _to_ it.

- Is content hidden behind login forms?
- Are you relying on search forms (instead of navigation menus)?
- Is text hidden within non-text content?
- Can search engines follow your site navigation?

>- Have a clean information architecture
>- Use sitemaps!

::: notes

-
- a list of links of everything on the website! Does not replace the need for a good IA, but can help crawlers

:::

### 2. Index {data-transition="slide-in fade-out"}

<div style="height:2em;"></div>

![The index is where the discovered pages are stored](img/index.svg){width="600"}

::: notes

Search engines process and store information they find in an index, a huge database of all the content they’ve discovered and deem good enough to serve up to searchers.

After a crawler finds a page, the search engine renders it just like a browser would. In the process of doing so, the search engine analyzes that page's contents. All of that information is stored in its index.

:::

### 2. Index {data-transition="fade"}

What is stored in the index?

![The cached version of any website is accessible through the SERP](img/google-cache.png){style="margin-top:1em;"}

::: notes

Can I see how a Googlebot crawler sees my pages?

Yes, the cached version of your page will reflect a snapshot of the last time Googlebot crawled it.

Google crawls and caches web pages at different frequencies. More established, well-known sites that post frequently like https://www.nytimes.com will be crawled more frequently than the much-less-famous website for Roger the Mozbot’s side hustle, http://www.rogerlovescupcakes.com (if only it were real…)

You can view what your cached version of a page looks like by clicking the drop-down arrow next to the URL in the SERP and choosing "Cached":

:::

### 2. Index {data-transition="fade-in slide-out"}

What is stored in the index?

![Check the text-only version](img/text-only.png){width="500"}

::: notes

You can also view the text-only version of your site to determine if your important content is being crawled and cached effectively.

:::

### 3. Rank {data-transition="slide-in fade-out"}

![&nbsp;](img/rank.jpg)

::: notes

Ordering of results from the index according to relevance.

To determine relevance, search engines use algorithms, a process or formula by which stored information is retrieved and ordered in meaningful ways. 

:::

### 3. Rank {data-transition="fade"}

![Each year, Google changes its search algorithm around 500–600 times](img/google-algorithm-update.png){width="700"}

::: notes

These algorithms have gone through many changes over the years in order to improve the quality of search results. Google, for example, makes algorithm adjustments every day — some of these updates are minor quality tweaks, whereas others are core/broad algorithm updates deployed to tackle a specific issue, like Penguin to tackle link spam.

While Google doesn’t always reveal specifics as to why they do what they do, we do know that Google’s aim when making algorithm adjustments is to improve overall search quality.


>Search engines [want to] provide useful answers to searcher's questions in the most helpful formats.

Reason for so many changes: search engines (still) learn. As with language: Eventually, with enough practice, the student knows the language well enough to even understand nuance, and is able to provide answers to even vague or incomplete questions.

When search engines were just beginning to learn our language, it was much easier to game the system by using tricks and tactics that actually go against quality guidelines. Take keyword stuffing, for example. If you wanted to rank for a particular keyword like “funny jokes,” you might add the words “funny jokes” a bunch of times onto your page, and make it bold, in hopes of boosting your ranking for that term:

:::

### 3. Rank {data-transition="fade"}

<div class="small" style="margin-top:2em;">
>Welcome to **funny jokes**! We tell the **funniest jokes** in the world. **Funny jokes** are **fun** and crazy. Your **funny joke** awaits. Sit back and read **funny jokes** because **funny jokes** can make you happy and **funnier**. Some **funny favorite funny jokes**.
</div>

<figure><figcaption>Keyword stuffing</figcaption>

::: notes
This tactic made for terrible user experiences, and instead of laughing at funny jokes, people were bombarded by annoying, hard-to-read text. It may have worked in the past, but this is never what search engines wanted.
:::

### 3. Rank: the role of links {data-transition="fade"}

![Types of links](img/links.svg){width="700"}

::: notes

Backlinks or "inbound links" are links from other websites that point to your website, while internal links are links on your own site that point to your other pages (on the same site).

Calculating the number of links pointing to any given site helped them do this. work very similarly to real-life WoM (Word-of-Mouth) referrals. 

:::

### 3. Rank: links (SEO _off-page_) {data-transition="fade"}

<div class="small">

- Referrals from others = good sign of authority  
- Referrals from yourself = biased, so not a good sign of authority
- Referrals from irrelevant or low-quality sources = not a good sign of authority and could even get you flagged for spam
- No referrals = unclear authority

</div>

<div class="fragment">

![Google PageRank](img/pagerank.png){width="300"}

</div>

::: notes
- Example: Many different people have all told you that Jenny’s Coffee is the best in town
- Example: Jenny claims that Jenny’s Coffee is the best in town
- Example: Jenny paid to have people who have never visited her coffee shop tell others how good it is.
- Example: Jenny’s Coffee might be good, but you’ve been unable to find anyone who has an opinion so you can’t be sure.

PageRank (part of Google's core algorithm) is a link analysis algorithm named after one of Google's founders, Larry Page. PageRank estimates the importance of a web page by measuring the quality and quantity of links pointing to it. The assumption is that the more relevant, important, and trustworthy a web page is, the more links it will have earned.

:::

### 3. Rank: content (SEO _on-page_) {data-transition="fade"}

>Does this page match the words that were searched and help fulfill the task the searcher was trying to accomplish?

No strict benchmarks on:

- length of content
- keyword density
- header tags

<div class="box fragment" style="width:300px;float:right;margin-right:2em;transform:rotate(10deg);text-align:center">
**FOCUS** should be on the users
</div>

::: notes

focus on user satisfaction and task accomplishment.All those can play a role in how well a page performs in search, but the focus should be on the users who will be reading the content.

:::

### 3. Rank: RankBrain {data-transition="fade" data-background="#595959"}

![Google RankBrain](img/rankbrain.jpg)

## Keyword research

---

https://moz.com/beginners-guide-to-seo/keyword-research

## The importance of quality content for SEO

### Low value tactics to avoid {data-transition="slide-in fade out"}

![Thin content](img/thin-content.svg){width="800"}

::: notes
Creating a page for every single one of the keywords in order to rank on page 1 for those highly specific queries.

Different pages even if they are essentialy saying the same thing, or for each city or region the company works on.

Not helpful for users, so addressed directly by Google on 2011. The assessment of quality content is a work in progress.

You should have a comprehensive page on a topic instead of multiple, weaker pages for each variation of a keyword.
:::

### Low value tactics to avoid  {data-transition="fade"}

![Duplicate content](img/duplicate-content.svg){width="800"}

::: notes
This can include taking content and republishing as-is, or modifying it slightly before republishing, without adding any original content or value.

Duplication is not penalized, but instead filtered now. Your page could just as well not show up at all on SERPs -- the original page would.
:::

### Low value tactics to avoid  {data-transition="fade"}

![Users were presented with a login screen in Spotify when searching for the National Philharmonic orchestra.](img/spotify1.png){width="600"}

::: notes
showing  a different thing to crawlers than to human visitors.

Spotify lost bt. 45-82% of their visibility in 2016 for this reason.
:::

### Low value tactics to avoid  {data-transition="fade"}

![Viewing Google's cached version of the page shows the content Spotify provided to the search engine](img/spotify2.png){height="450"}

### Low value tactics to avoid  {data-transition="fade-in slide-out"}

![Keyword stuffing](img/keyword-stuffing.png)

::: notes
Many people mistakenly think that if you just include a keyword within your page’s content X times, you will automatically rank for it. 

If a page is going to be valuable to users, it won’t sound like it was written by a robot, so incorporate your keywords and phrases naturally in a way that is understandable to your readers.
:::

<!-- https://moz.com/beginners-guide-to-seo/on-page-seo -->

### Site structure {data-transition="slide-in fade-out"}

Highly important for both

<div class="box center" style="padding-top:0;margin-bottom:.6em;">
usability <span style="width:25px;display:inline-block;font-size:2em;padding:0 .6em;vertical-align:baseline"><svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="plus" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" class="svg-inline--fa fa-plus fa-w-14 fa-2x"><path fill="currentColor" d="M416 208H272V64c0-17.67-14.33-32-32-32h-32c-17.67 0-32 14.33-32 32v144H32c-17.67 0-32 14.33-32 32v32c0 17.67 14.33 32 32 32h144v144c0 17.67 14.33 32 32 32h32c17.67 0 32-14.33 32-32V304h144c17.67 0 32-14.33 32-32v-32c0-17.67-14.33-32-32-32z" class=""></path></svg></span> findability / SEO
</div>

<figure style="text-align: right"><figcaption>
Marieke van de Rakt, [Site structure: the ultimate guide](https://yoast.com/site-structure-the-ultimate-guide/)</figcaption></figure>

::: notes
- The structure of the site (IA) has a significant impact on the UX. Navigating should be easy. You need to categorize and link your posts and products so they are easy to find. New visitors should be able to instantly grasp what you’re writing about or selling.
- Improves chances of ranking, helps search engines 'understand' the site
:::

### Site structure {data-transition="fade"}

The homepage

Classifying links: navigation menu, breadcrumbs, categories/tags

Contextual links

::: notes
Homepage: on top of the pyramid. Most important pages should be linked from the homepage.

- visitors more likely to end up there
- show Google that they are important

Contextual: internal links in the text, relevant for someone reading the current page. The importance of CONTEXT
:::

### Page structure

Header tags: there is only one `<h1>` (should be unique)

Use sub-topics according to keyword hierarchy

Internal links: anchor text, context, volume

::: notes
h1 should contain the primary keyword or phrase

link vol: limit the number of links on a page to a reasonable number
:::

Copywriting https://yoast.com/complete-guide-seo-copywriting/