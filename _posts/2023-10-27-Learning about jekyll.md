---
title: Learning about Jekyll
date: 2023-10-27 20:37:12 +0000
categories: #[TOP_CATEGORY, SUB_CATEGORY]
tags: #[TAG]     # TAG names should always be lowercase
---

## Beginning the project

I've understood how websites work on the surface level since I was a teenager.
At various times, I've started HTML documents and got them to display on a browser — simple text and images.
But it still annoyed me that I couldn't see how you'd jump from that to a shop page with reactive windows and custom animations.
So after thinking about this from time to time, I finally decided to spend enough time learning how to build a site.
The goal was/is a personal repository of past projects and some general information about myself.

## Starting Simple

At first, I got interested in CSS.
I was inspired by the work of [Hyperplexed](https://www.youtube.com/Hyperplexed) and tried to recreate some of their suggestions myself.
My purpose was to get experience, and to achieve that I had to complete a small CSS task as presented, then try to modify it or add a personal element. More detail on how that went in the post about [Playing with CSS]({% post_url 2023-07-12-Playing with CSS%}).

## Discovering Jekyll

I talked to friends and took inspiration from other sites until I stumbled upon 11nty as a simple static site generator.
It looked easy to learn, and it boasted performance.
So I navigated to GitHub and started looking into hosting one of their GitHub pages.
There I discovered that GitHub integrates well with [Jekyll](https://jekyllrb.com/), and I would have to adjust many of their instructions to retrofit 11nty where Jekyll lived.
So, since I haven't spent any time in either static site generator, I ended up going with Jekyll.
I don't have the experience to be able to compare the two, although if I ever take up a new project, I might try 11nty so that I can see if I have an easier time getting started.

### Experimenting with Themes

Part of what attracted me to Jekyll is the available themes.
I had spent time in the past making decisions on how I wanted my site to look.
This took a lot of time I was willing to reinvest to port into Jekyll.
However, GitHub showed that there are existing themes out there, and it was surprisingly easy to find a theme that was close enough to what I wanted to achieve.
I ended up with the Chirpy theme and spent some time trying to migrate my existing first draft from the default theme to Chirpy.
This led me to discover that Chirpy is using a newer version of Jekyll than GitHub-pages, and therefore the GitHub workflow that exists would not build properly.

Although this was discouraging, I tried multiple ways of integrating Chirpy and automating the building and deployment of the site.
I ended up with an approach where I would build the assets locally, and have a script to upload them to a separate branch, where the site lived.
Even so, the implementation of the Chirpy theme wasn't all there, and I was having configuration issues.
So I bit the bullet, renamed and archived the repository, and started from scratch using the Chirpy template repository.
It was a breath of fresh air.

### Customisation

```bash
# Hierarchy of organisation for the site generator
Jekyll # using Chirpy
├── Liquid # Parser to configure Jekyll and the Chirpy theme
│   ├── Rouge # CSS Styles configuration?
│   └── Ruby # Builds the HTML/SCSS/Js assets
└── kramdown # Converts MD documents to HTML
```

Having set up the theme, I immediately realised that some of the changes I wanted to perform were non-modifiable unless the theme itself was edited.
After I made all the modifications I wanted, I built the site locally instead of deploying it through GitHub.
Then I uploaded it to its own branch.

Now adding new posts doesn't rely on anything besides markdown, so this procedure can be automated again.
I did need to capture the [changes](/assets/files/custom-jekyll-theme-chirpy-6.2.3.zip), as updating the Gem theme file from Ruby would wipe them all.
Other than that, the only other things I needed to tweak were the `_config.yml, contact.yml, and  share.yml` files, the names of the tabs, and the data in the _assets_ folder.
