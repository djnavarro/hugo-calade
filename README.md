SLURM
================

**SLURM** is a Hugo theme that adapts the **Xmin** theme. The original
theme is intended to be e**X**tremely **MIN**imal. This extension is an
attempt to be **S**lightly **L**ess **U**n**R**emittingly **M**inimal.
My main goal though was to make sure I understand the basics of how Hugo
works.

## Getting started

To create the example site using the SLURM template into a fresh
directory:

``` r
site <- here::here("my_site")
blogdown::new_site(dir = site, theme = "djnavarro/hugo-slurm") 
```

To serve an existing site:

``` r
setwd(site)
blogdown::serve_site()
```
