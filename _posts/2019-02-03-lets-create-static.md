---
layout: post
title:  "Let's create a static website : in only 3 steps."
author: sal
categories: [ Wordpress Guide ]
<!--image: https://images.unsplash.com/photo-1528784351875-d797d86873a1?ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80 -->
image: assets/images/website-5725734_1280.png
tags: [wordpress]
---


*how can create free static website with free hosting.*

## you are just 3 step far from launching your first Static website.
*The web development area is very vast. According to [wikipedia](https://en.m.wikipedia.org/wiki/List_of_programming_languages) more than seven thousand plus programming Languages exists in 2020 athough few of them are used day by day out of 7 thousand, less than 50 languages which is being popularly used.*

**So, before Dive into the Topic I assume everyone is aware of [static]( https://www.google.com/amp/s/techterms.com/amp/definition/staticwebsitevs) and Dynamic websites. I will give you short intro about static vs dynamic websites** but won't dig deeper .

### Static vs Dynamic?
Static websites loads faster because it runs on local server without database, no database enquiries , no template engine files can be cached and served immediatiely upon Request. While [dynamic](https://www.templatemonster.com/blog/what-is-dynamic-website/#:~:text=A%20dynamic%20website%20is%20a,consumer%20interplay%2C%20or%20day%20time.) files changed on server and then served to its users.

### what you'll need Before creating a static website.
It's the easiest way to create your static website.

- [Github account](https://github.com/).
- some best static site generators like [Jekyll](https://jekyllrb.com/docs/) , Hugo , 11ty but I would suggest [Stackbit](https://www.stackbit.com/)if you are completely new in development field . stackbit provides Live page preview while editing. However [Forestry.io](https://forestry.io/) does the same but doesn't gives live preview while editing. You have to manually change every files .

> Start with one click [check Live Demo](https://themes.gohugo.io/theme/hugo-lodi-theme/)

- Netlify account it's a Free platform. Netlify gives you a platform where you can host your website. Their serverless cloudhosting platform widely used by static site generators also there Content delivery Network deployment pipeline with a single workes makes them Fast.
- it gives you free SSL.
- netlify is free.
- serverless backend you can access by everywhere.
asset optimization for js minify and CSS.
- free plugins however you can upgrade to premium . Or you can create your own plugins.
- the best part is every documenting you can find on Github if you have ever stucked up.

So now we a're aware about our essential need:

1. [Github](https://github.com) it will contain & secure your file.

2. [Stackbit](https://stackbit.com) headless cms you can edit your text, files everything.

3. [Netlify](www.netlify.com) deploy and publish your site.

## start with Github account signup if you don't have or login:
### step1:

Start with one click check Live Demo. Or search for theme I will address you a Free [minimal portfolio theme](https://github.com/luizdepra/hugo-coder) Fork it you will find the fork tab on right extreme corner. Now it's added to your Repository now goto the bottom of the page and click on Create with stackbit. as soon as you click on that button you will be redirected to stackbit platform.

## Choose your headless CMS Platform.
### Step 2.

Let's start with stackbit registered Yourself Choose the platform like Jekyll , [11ty], Hugo now choose your CMS and good to go with sanity And pick up the lightest version after connecting with sanity it bundele up all your files and gives you interface to edit your site.

## final step: Deploy your website on Netlify.
### Step 3.

Connect your site with Github account and choose a project repository if you don't have any account still you can deploy new site there drag and drop interface provides you facility connecting new sites without github. Now you have all integrated files on one place .

`Note:However these setups were basic now you will find some challenging work .`

- you have to learn some [basic Markdown syntax](https://www.markdownguide.org/basic-syntax/)to create a new post . You can Learn in just 3 min here I wanna inform you markdown is a substitute of html Language because Hugo runs on unibit and the extension is .toml
- github doesn't allow you to upload your files how you can?
- how to embed youtube video's?
- How to change your subdomain with netlify because your default url will be like yoursite-name.app.io
if you are using basic templates they doesn't provide you sharing and comment section.
How to do Syntax highlighting for fenced code blocks example :


```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

So I will cover all these challenges in next tutorial , stay tuned with me . Thanks for Reading! :octocat:








