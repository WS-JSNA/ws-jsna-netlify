---
layout: single # This is the layout you'll use most of the time
permalink: /generic_post/ # This is where you'll be able to find the page after commit
title: "Generic Post with all the features"
sidebar:
    nav: "coastal-GPS-selected"
# You can find the names of different sidebars in _data/nav.yml
toc: true
toc_sticky: true
---
# Generic post with all the features

Note that putting an `<h1>` tag at the start of your file will look a bit odd in this theme.

This post aims to show off some of the other features I've put into the site. Another good port of call is the example pages for the [minimal mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

## Sidebar

You can find the names of different sidebars in `_data/nav.yml` or write your own and save it in that file.

## A bit in the middle with placeholder text

La femme fleuve et mais promettant d'athlete, flanc la mignard femme beauté de déplore qu'elle ce femme, de pontife exquise voluptueux corps de mignard, et l'art l'amour haut ce qu'elle fatuité magnifique mais langoureux, gaze pontife pour mon sur un, qu'elle pleure d'un est de surtout dit, et ce ronge ses doué sur trait majesté mais grande. Dit par de l'ondulation trôner qu'un face la un m'appelle. Genre beauté prince qu'elle quel de hélas. C'est m'enivre qui yeux beauté vainqueur gaze ce les. Visage volupté jaillir extase bonheur quel trôner nous. Douleur mais prince un véritable par. Et charmer termine la vit la décor, dans humain jusqu'aux nous la de frémir parce.

Raven back beguiling whom gloated ever and all here radiant. Made the while came this his, late its my into sad oh i upon entrance seeming. I door nevermore unbroken truly. Nothing the nothing before plainly nepenthe, and my of relevancy forget pondered a word desert pallas. Devil nevermore perfumed angels shore entreating in. Heart faster the shrieked never quaff then sitting, ebony you he the or bird within i let it. Oer i it said both take peering was. Truly than this is of, is from.

## A table of contents

The table of contents will use all the heading elements in the markdown or HTML and give you jump links down the side to reach those points in the document.

## An embedded PDF

Let's embed one of the PDFs from the JSNA site right here. The code snippet `{% include embedpdf file_path="/assets/core/Median_age_wsx_districts_2016.pdf" width="650" height="525" caption="This is my caption, I should probably say something here about what this figure or document is." %}` should do the job for us.

{% include embedpdf file_path="/assets/core/Median_age_wsx_districts_2016.pdf" width="650" height="525" caption="This is my caption, I should probably say something here about what this figure or document is." %}

Change the `file_path` variable to the location of the file you want to embed. Note that the snippet itself doesn't check whether you're embedding something embedable, so you will have to be careful. (Exercise: Why not try to break it by using weird formats like Word Documents and MP3s?)

Note that the `file_path` can also include files hosted elsewhere, so we can embed external reports relevant to documents.

## An embedded map or two

The code `{% include htmlwidget_map html_path="/assets/htmlwidgets/WSx_GPs_CCG_Localities-1.html" %}` includes a default caption that lets people with antiquated browsers or overzealous security settings see that there's supposed to be a map there.

{% include htmlwidget_map html_path="/assets/htmlwidgets/WSx_GPs_CCG_Localities-1.html" %}

There's another code that's more basic `{% include htmlwidget_w_cap html_path="/path/to/widget/" caption="This is the caption" %}` where you can write your own caption, if needed.

Note that you don't need to specify the height or width of HTML embeds. JavaScript in the theme makes the embeds responsive (i.e. they scale to the width of the browser). All embeds created this way should be visible on tablets and smartphones.

## The figure tag

This code helps us present figures with captions in a HTML `<figure>` tag. This means that our figures will work nicely with screen readers and be better understood by viewers of our pages.

The code looks like this: `{% include figure image_path="/assets/images/ccg-profiles/horsham/HMSx-Childhood-obesity-year-6.gif" caption="Source: PHE Fingertips (NCMP data)" alt="Source: PHE Fingertips (NCMP data)" class="full" %}`

This produces:

{% include figure image_path="/assets/images/ccg-profiles/horsham/HMSx-Childhood-obesity-year-6.gif" caption="Source: PHE Fingertips (NCMP data)" alt="Source: PHE Fingertips (NCMP data)" class="full" %}

Note: I learned after I'd finished the site that you shouldn't include both `alt` and `figcaption` tags together as this might confuse screen readers. I'll take care of this in an accessability audit later.

## Notices

The theme includes CSS definitions for creating coloured callouts in the main text. These can assist the reader in understanding but are also peppered throughout the site as excuses for broken links, i.e. `{% include wip_notice %}`

which produces:

{% include wip_notice %}

You can create more general notices with the following markdown syntax:

```{markdown}
This is my paragraph. For more ways of styling the box [have a look at the minimal mistakes article describing them](https://mmistakes.github.io/minimal-mistakes/post%20formats/post-notice/). {: .notice--warning}
```

This is my paragraph. For more ways of styling the box [have a look at the minimal mistakes article describing them](https://mmistakes.github.io/minimal-mistakes/post%20formats/post-notice/). {: .notice--warning}

Note that you use the `{: .class}` syntax to apply CSS classes to markdown. Because I've written CSS classes that mimic the themes of the old website, I can create something you might call a "starting well box":

```{markdown}
All children in West Sussex to receive a free ice cream. {: .notice--starting-well}
```

All children in West Sussex to receive a free ice cream. {: .notice--starting-well}

I also created boxes for the living well, ageing well, and reports colours.

## Tables

For tables, you can read [this post on the kramdown documentation site](https://kramdown.gettalong.org/syntax.html#tables). (Kramdown is the markdown parser that the website uses to render markdown to HTML.)