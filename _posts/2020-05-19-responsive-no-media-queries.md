---
title: Responsive website with no media queries
published: true
layout: post
img: post-books-ux-design.jpg
excerpt: A fully responsive site without media queries using Flexbox and CSS Grid.
---
I finally redesigned this website. The challenge was to do a fully responsive site without media queries using [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/){:target="_blank"} and [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/){:target="_blank"}.

![Visual explorations for the new  website]({{site.baseurl}}/images/responsive-no-media.gif)*Responsive design without media queries*

This the 3rd version of this site. The first version of this website was done hand-coded by me, following the instructions from [Ethan Marcotte](https://ethanmarcotte.com){:target="_blank"} and his book [Responsive Web Design](https://abookapart.com/products/responsive-web-design){:target="_blank"}. The second version was made using [ Jekyll-now](https://www.jekyllnow.com){:target="_blank"} to include a blog section to the site using the standard theme, and what you are seeing now is version 3.

A while a go, I read an article from [Juan Martin García](https://www.juangarcia.design){:target="_blank"} titled [“Look Ma, no media Queries”](https://css-tricks.com/look-ma-no-media-queries-responsive-layouts-using-css-grid/){:target="_blank"} and I was determined to try it on my website. I thought that it could be a great way to learn more about CSS grid. Also, I am a firm believer that we should design not for devices but based on the content and where it breaks, so the idea of being able to make the whole website responsive without having to worry about different device-based breakpoints sounded fantastic.

Before I jumped into creation mode, I first wanted to think about the redesign in terms of layout and visual style. The previous version was super basic, a 1 column layout that just grew vertically. This looked like a good opportunity to try something different and test the limits of what was possible with this "no media queries" approach.

![Visual explorations for the new  website]({{site.baseurl}}/images/post-responsive-explorations.jpg)*Explorations as a form of procrastination*

This exploration mode went on for some time, and it became a form of procrastination. After a while I decided to move on, since anything different from what I had online was definitively an improvement.

Fast forward to February 2020, I went to the [AWWWARDS conference](https://conference.awwwards.com){:target="_blank"} in Amsterdam and listened to [Robin Noguier](https://robin-noguier.com){:target="_blank"} give a talk about side projects, and the idea of “consistency over intensity” got stuck in my mind as a way to finish the website. I scheduled an hour every day to work on it, and split the work in small tasks that I could tackle in this short blocks of time.

The first part I had to do was translate the design into the html structure, and make it responsive without media queries as shown on the article. That came with some challenges based on my design. It meant making changes to the design to accomplish the goal (remember… no media queries) and without falling again into procrastination mode.

![Testing the html content break points]({{site.baseurl}}/images/video-responsive-no-media2.gif)*Testing the html content break points*

The second part was making it work with [Jekyll](https://jekyllrb.com){:target="_blank"}, which I wanted to continue to use to write blog articles. I wanted to have my content in a place I could control, tinker with and use as a tool for communication and learning. This was a bit more intimidating since I am not a developer. Jekyll is based on [Liquid](https://shopify.github.io/liquid/){:target="_blank"} for the templating system, which turned out not to be so hard to modify and adapt to my needs.

![Writing the CSS]({{site.baseurl}}/images/post-responsive-css-atom.png)*Writing the html and CSS in Atom, it's a bit messy, I know*

As a final push, I wanted to improve how the site font scaled in the different resolutions. I was already using scalable sizes (rem and em values that adapt to the text container or the base font size) but in some cases the result wasn't what I expected. By looking for ways to solve this, I found this [Simplified fluid typography](https://css-tricks.com/simplified-fluid-typography/){:target="_blank"} approach that aligned well with what wanted to do. By defining a minimum and maximum font size as limits, but the actual size would change based on the width of the screen. (You won't be able to see it if you try resizing this page, unless you refresh the page).

So this is it, a fully responsive personal website, blog capabilities without media queries or breakpoints defined by a device but its content. As the previous one, it’s not done and not great visually either, I will play with it, add functionality and evolve it based on what I want to learn or express.

I have learned a lot along the process and it has given me a different perspective on what can be done with this new technologies in terms of layout and responsive design. I am specially happy about making the time to get it done and sharing it with the world, even if its far from perfect.

## Thank You!

I have to thank [Rachel Andrews](https://rachelandrew.co.uk){:target="_blank"} for her great explanations of CSS Grid, [CSS-tricks](https://css-tricks.com){:target="_blank"} for their flex-box and grid guides and the open nature of the web that allowed me to peek into other websites by inspecting the html. Here are some of the resources I used if you want to give it a try:

- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/){:target="_blank"}
- [A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/){:target="_blank"}
- [Look Ma no Media Queries](https://css-tricks.com/look-ma-no-media-queries-responsive-layouts-using-css-grid/){:target="_blank"}
- [Create a responsive grid layout with no media queries, using CSS Grid](https://hankchizljaw.com/wrote/create-a-responsive-grid-layout-with-no-media-queries-using-css-grid/){:target="_blank"}
- [Simplified fluid typography](https://css-tricks.com/simplified-fluid-typography/){:target="_blank"}
