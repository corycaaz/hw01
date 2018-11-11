# Homework 1 for MACS 30500
Maybe you're a student reading this. Perhaps you are like me, a young social scientist finally deciding to return to school. If so, listen to me: you can prepare for graduate training right now, today, with open source material.

I am very thankful for [Ben Soltoff's](http://www.bensoltoff.com/) contribution to my career as a psychological scientist. He provides [this course online](https://cfss.uchicago.edu/index.html). A motivated student can teach himself quite a bit. Even though I will not receive college credit, or an explicit review by the instructor, it is important to follow along with the material for **Computing for the Social Sciences**. These assignments will provide foundational skills for advanced statistical inference and reproducibility.

Watch out, graduate committee! *This* student will enter your program with strong quantitive skills (just ignore that GRE score).

> But wait, don't you live in Atlanta? How on earth did you find out about this graduate-level course offered by the University of Chicago?

## Open Source Masters Degree
This is how I got to GitHub and MACS 30500. 

As a volunteer research assistant at Columbus State University, my advisor, Dr. Brandt A. Smith, encouraged me to explore R. So, I did, starting with free resources like [Open Stats Lab](https://sites.trinity.edu/osl/). If you haven't yet, I suggest checking out these activities assembled by Kevin McIntyre. They use realworld datasets from the prestigious journal *Psychological Science*. Upon reading many of these articles, I discovered that:

1. the field of psychology is pushing for open source materials and open data; and
2. if I plan to be a competitive candidate for tenure-track positions, then I better hop on this bandwagon early.

Eventually I found [DataCamp](https://www.datacamp.com), and my skills as a blossoming data scientist increased exponentially. Seriously. What a great platform for those of us with a *very limited* background in coding.

After taking many of the courses offered by DataCamp, I came across other open source avenues to expand my ken. I won't mention them all, but here's a few:

* The [Modern Dive][1] open source textbook for statistics and data science.
* Need a GUI for simple, quick analysis built on R? [Learn how to use JASP][2] with hands-on practice.
* Of course, you can read [R for Data Science][3], which I believe this course uses.
*    Then there's [Kaggle][4] if you want to discover how to utilize trending algorithms and practice with Jupyter notebooks.
    Note, thanks to Rachel Tatman's [learning kernels][kaggle r], I was able to find MAC 30500. Thank you, Rachel!
* Finally, try [OpenIntro][open intro], both a free textbook and an R package.

The very idea of pursuing an [open source masters degree][osdsm] is indebted to [Clare Corthell][clare].

## Code
Some of my favorite R package so far are `tidyverse`, `broom`, and `psych`. 

Also, here's a tip if you are assigning new variable and would like the value to print to the console. There's no need to type the new variable again under the assignment, like this:

```r
variable <- data.frame(a = c(12, 16, 39), b = c(13, 15, 38))
variable
```

Instead, you can simply wrap the assignment with `()`.

```r
(variable <- data.frame(a = c(12, 16, 39), b = c(13, 15, 38)))
```

For future work, especially if working with a team of researchers, it may be helpful to create a task list.

- [ ] Read *New York Times* article
- [x] Setup GitHub
- [x] Home work 1

[1]: https://moderndive.com/
[2]: https://osf.io/t56kg/
[3]: https://r4ds.had.co.nz/index.html
[4]: https://www.kaggle.com/
[kaggle r]: https://www.kaggle.com/learn/r
[open intro]: https://www.openintro.org/
[osdsm]: http://datasciencemasters.org/
[clare]: https://github.com/datasciencemasters/go