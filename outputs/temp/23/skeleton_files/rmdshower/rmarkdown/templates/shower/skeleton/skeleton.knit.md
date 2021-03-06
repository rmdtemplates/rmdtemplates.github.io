---
title: "Shower Presentations with R Markdown"
author: https://github.com/mangothecat/rmdshower
ratio: 16x10
output:
  rmdshower::shower_presentation:
    self_contained: false
    katex: true
    theme: ribbon
---

# Shower Presentations with R Markdown { .white }

<p class="white">
Get it from GitHub: https://github.com/mangothecat/rmdshower.
</p>

# R Markdown

This is an R Markdown presentation. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on using R
Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code chunks
within the document.

# Shower

These slides use a template from the [shower](https://github.com/shower/shower)
presentation system. Notable features:

1. Works in all modern browsers
1. Presentation fully keyboard accessible
1. Multiple themes available
1. Printable to PDF

<p class="note"> Shower ['ʃəuə] noun. A person or thing that shows.</p>

# Slide with Plain Text

Let me see your identification. You don't need to see his
identification. We don't need to see his identification. These are not the
droids your looking for. These are not the droids we're looking for. He can
go about his business. You can go about your business.

Move along. Move along. Move along.

# Two column layout


<p class="double">
What is it? Your fathers lightsaber. This is the weapon of a Jedi
Knight. Not as clumsy or as random as a blaster. An elegant weapon for a
more civilized time. For over a thousand generations the Jedi Knights were
the guardians of peace and justice in the Old Republic. Before the dark
times, before the Empire. How did my father die? A young Jedi named Darth
Vader, who was a pupil of mine until he turned to evil, helped the Empire
hunt down and destroy the Jedi Knights.
</p>

# Two column layout, independent columns

<div class="double">
<p class="double-flow">
How did I get into this mess? I really don't know how. We seem to be made
to suffer.
</p><p class="double-flow">
It's our lot in life. I've got to rest before I fall apart.
</p>
</div>

# Lists

1. Simple lists are marked with bullets
1. Ordered lists begin with a number
1. You can even nest lists one inside another
    * Or mix their types
    * But do not go too far
    * Otherwise audience will be bored
1. Look, seven rows exactly!

# Formulas

Formulas are rendered by KaTeX, https://github.com/Khan/KaTeX

It supports both inline: \(y = x / 2\) and displayed formulas:

\[ x_{1,2} = \frac{- b \pm \sqrt{b^2 - 4ac}}{2a} \]

# Slide with quote

> The bad news is that when ever you learn a new skill your going to
> suck. It's going to be frustrating. The good news is that is typical and
> happens to everyone and it is only temporary. You can't go from knowing
> nothing to becoming an expert without going through a period of great
> frustration and great suckiness.

**Hadley Wickham **

# Slide with R Code and Output


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

# Tables

|                   |  mpg  |  cyl  |  disp  |  hp  |
|:-----------------:|:-----:|:-----:|:------:|:----:|
|     Mazda RX4     | 21    |   6   |  160   | 110  |
|   Mazda RX4 Wag   | 21    |   6   |  160   | 110  |
|    Datsun 710     | 22.8  |   4   |  108   |  93  |
|   Hornet 4 Drive  | 21.4  |   6   |  258   | 110  |
| Hornet Sportabout | 18.7  |   8   |  360.0 | 175  |
|       Valiant     | 18.1  |   6   |  225.0 | 105  |
|      Duster 360   | 14.3  |   8   |  360.0 | 245  |

# Pictures { .white }

<img src="scifi.jpg" class="cover">

<p class="white">
And text on top of them.
</p>

# Title slide { .shout }

---

## You Can Shout If You Want To { .shout .shrink }

# Lists item by item

> 1. Lets you reveal list items one by one
> 2. To keep some key points
> 3. In secret from audience
> 4. But it will work only once
> 5. Nobody wants to see the same joke twice

# Slide with Plot

<img src="/Users/haozhu/Documents/pub_projects/rmd_templates/outputs/temp/23/skeleton_files/figure-revealjs/unnamed-chunk-2-1.svg" width="768" />

# Full Page Plots { .shout }

# { .fullpage }

<div class="fullpage width">
<img src="/Users/haozhu/Documents/pub_projects/rmd_templates/outputs/temp/23/skeleton_files/figure-revealjs/unnamed-chunk-3-1.svg" width="768" />
</div>

# More information

## About R markdown: http://rmarkdown.rstudio.com

## About shower: https://github.com/shower/shower

## Example shower presentation: http://shwr.me/
