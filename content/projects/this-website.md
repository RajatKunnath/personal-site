---
title: "This Website"
date: 2026-11-17T20:01:30+05:30
summary: "A brief insight into the creation of this website."
tags: ['tech']
draft: false
---

For those of you who don't know, I've had a blog since 2022 at [www.rajatsblog.com](https://www.rajatsblog.com), which moved to [this domain](https://www.rajatkr.com) in 2026. Back then, I used Wix, a WYSIWYG (What You See Is What You Get) editor. It was convenient at first, but it gradually became a pain to maintain and customize. This year, when I felt like starting over, I decided not to go with Wix.

This time I built my website with Hugo, a free and open-source tool, along with the popular Congo theme. Hugo is fun because it's plain and simple, and it requires no extra knowledge. All you need is a basic understanding of HTML and Markdown, plus some CSS to make your site look fancy. That said, it wasn't all sunshine and rainbows. For someone with no prior web hosting experience, figuring out where and how to host was a challenge. Thankfully, Claude gave me a wonderful free solution that works phenomenally well. It recommended Cloudflare Pages, which is free forever, so the only thing I have to pay for is the domain. Super sweet.

Setting up the blog was a breeze, but adding features like email newsletters and migrating posts from my previous site was quite challenging. Setting up newsletters on Wix was easy, but with Hugo you have to do everything yourself. The main issue was the plethora of options on the market. I tinkered with several services and finally settled on Brevo, as it seemed to offer more customizability and modularity.

The next hurdle was migrating the posts from my old website. I naively assumed I could just copy all the posts, with their metadata, from the RSS feed, but it turns out Wix doesn't allow that. It's very easy to migrate your site to Wix, but very, I mean VERY, hard to get your content off their platform (to hell with Wix!). Fortunately, someone on Reddit figured out that you can extract all the posts, with images and correct formatting, using Wix's API. He didn't explain how to do it or which documentation to follow, so I did the most logical thing and asked Claude for help. Claude generated a nice little bash script that asks for the API credentials and outputs all the articles, properly formatted. You can find them here: [Archive](/archive).

This is how I created my website, and I hope you don't find it all that ugly. I'm always looking for ways to make the site more efficient and impressive. I think it's still a bit gimmicky, but for now I'm pretty satisfied with how it turned out. One of the main things I haven't figured out is a good, foolproof commenting system. I'd love to integrate one, but most services are either too expensive or too heavy for my site. Do let me know if you have any suggestions or ideas. You can find the repo for this website on my [GitHub](https://github.com/RajatKunnath/personal-site). Happy surfing!
