Introduction to Generative Art
================

``` r
#color palettes implemented in aRtsy
colors = c("blackwhite","bell","boogy1","boogy2","boogy3",
           "dark1","dark2","dark3","flora","house","jasp",
           "jfa","jungle","klimt","kpd","lava","origami",
           "mixer1","mixer2","mixer3","mixer4","nature",
           "neon1","neon2","retro1","retro2","retro3","retro4",
           "sooph","sky","tuscany1","tuscany2","tuscany3",
           "vrolik1","vrolik2","vrolik3","vrolik4","vrolik5"
           )
```

# Iterative collection

``` r
canvas_ant(colors = colorPalette("mixer2"))
```

![](introductory_files/figure-gfm/iteractive_collection-1.png)<!-- -->

``` r
canvas_cobweb(colors = colorPalette("tuscany3"))
```

![](introductory_files/figure-gfm/iteractive_collection-2.png)<!-- -->

``` r
canvas_collatz(colors = colorPalette("bell"))
```

![](introductory_files/figure-gfm/iteractive_collection-3.png)<!-- -->

``` r
canvas_chladni(colors = colorPalette("boogy2"))
```

![](introductory_files/figure-gfm/iteractive_collection-4.png)<!-- -->

``` r
canvas_flow(colors = colorPalette("dark2"))
```

![](introductory_files/figure-gfm/iteractive_collection-5.png)<!-- -->

``` r
canvas_maze(color = "#fafafa")
```

![](introductory_files/figure-gfm/iteractive_collection-6.png)<!-- -->

``` r
canvas_petri(colors = colorPalette("house"))
```

![](introductory_files/figure-gfm/iteractive_collection-7.png)<!-- -->

``` r
canvas_planet(colors = colorPalette("retro3"))
```

![](introductory_files/figure-gfm/iteractive_collection-8.png)<!-- -->

``` r
canvas_splits(colors = colorPalette("origami"))
```

![](introductory_files/figure-gfm/iteractive_collection-9.png)<!-- -->

``` r
canvas_stripes(colors = colorPalette("random", n = 10))
```

![](introductory_files/figure-gfm/iteractive_collection-10.png)<!-- -->

``` r
canvas_strokes(colors = colorPalette("nature"))
```

![](introductory_files/figure-gfm/iteractive_collection-11.png)<!-- -->

``` r
canvas_phyllotaxis(colors = colorPalette("neon2"))
```

![](introductory_files/figure-gfm/iteractive_collection-12.png)<!-- -->

``` r
canvas_recaman(colors = colorPalette("sooph", n = 10))
```

    ## Warning in colorPalette("sooph", n = 10): attempt to select more colors than
    ## are available in this palette, returning the requested palette with the maximum
    ## number of colors

![](introductory_files/figure-gfm/iteractive_collection-13.png)<!-- -->

``` r
canvas_turmite(colors = colorPalette("dark2"))
```

![](introductory_files/figure-gfm/iteractive_collection-14.png)<!-- -->

``` r
canvas_watercolors(colors = colorPalette("vrolik4"))
```

![](introductory_files/figure-gfm/iteractive_collection-15.png)<!-- -->

# Geometric collection

``` r
canvas_diamonds(colors = colorPalette("lava"))
```

![](introductory_files/figure-gfm/geom_collection-1.png)<!-- -->

``` r
canvas_function(colors = colorPalette("jfa"))
```

![](introductory_files/figure-gfm/geom_collection-2.png)<!-- -->

``` r
canvas_polylines(colors = colorPalette("klimt"))
```

![](introductory_files/figure-gfm/geom_collection-3.png)<!-- -->

``` r
canvas_ribbons(colors = colorPalette("jasp"))
```

![](introductory_files/figure-gfm/geom_collection-4.png)<!-- -->

``` r
canvas_segments(colors = colorPalette("sky"))
```

![](introductory_files/figure-gfm/geom_collection-5.png)<!-- -->

``` r
canvas_squares(colors = colorPalette("random",n=10))
```

![](introductory_files/figure-gfm/geom_collection-6.png)<!-- -->

# Supervised collection

``` r
canvas_blacklight(colors = colorPalette("mixer4"))
```

![](introductory_files/figure-gfm/supervised-1.png)<!-- -->

``` r
canvas_forest(colors = colorPalette("retro2"))
```

![](introductory_files/figure-gfm/supervised-2.png)<!-- -->

``` r
canvas_gemstone(colors = colorPalette("origami"))
```

![](introductory_files/figure-gfm/supervised-3.png)<!-- -->

``` r
canvas_mosaic(colors = colorPalette("tuscany1"))
```

![](introductory_files/figure-gfm/supervised-4.png)<!-- -->

``` r
canvas_nebula(colors = colorPalette("dark1"))
```

![](introductory_files/figure-gfm/supervised-5.png)<!-- -->

# Static collection

``` r
canvas_circlemap(colors = colorPalette("vrolik2"))
```

![](introductory_files/figure-gfm/static-1.png)<!-- -->

``` r
canvas_mandelbrot(colors = colorPalette("random",n=5))
```

![](introductory_files/figure-gfm/static-2.png)<!-- -->

# Color palettes

``` r
#try different color palettes
for (color in colors){
  print(paste("Color palettes:",color))
  print(canvas_circlemap(colors = colorPalette(color)))
  
}
```

    ## [1] "Color palettes: blackwhite"

![](introductory_files/figure-gfm/colors_exp-1.png)<!-- -->

    ## [1] "Color palettes: bell"

![](introductory_files/figure-gfm/colors_exp-2.png)<!-- -->

    ## [1] "Color palettes: boogy1"

![](introductory_files/figure-gfm/colors_exp-3.png)<!-- -->

    ## [1] "Color palettes: boogy2"

![](introductory_files/figure-gfm/colors_exp-4.png)<!-- -->

    ## [1] "Color palettes: boogy3"

![](introductory_files/figure-gfm/colors_exp-5.png)<!-- -->

    ## [1] "Color palettes: dark1"

![](introductory_files/figure-gfm/colors_exp-6.png)<!-- -->

    ## [1] "Color palettes: dark2"

![](introductory_files/figure-gfm/colors_exp-7.png)<!-- -->

    ## [1] "Color palettes: dark3"

![](introductory_files/figure-gfm/colors_exp-8.png)<!-- -->

    ## [1] "Color palettes: flora"

![](introductory_files/figure-gfm/colors_exp-9.png)<!-- -->

    ## [1] "Color palettes: house"

![](introductory_files/figure-gfm/colors_exp-10.png)<!-- -->

    ## [1] "Color palettes: jasp"

![](introductory_files/figure-gfm/colors_exp-11.png)<!-- -->

    ## [1] "Color palettes: jfa"

![](introductory_files/figure-gfm/colors_exp-12.png)<!-- -->

    ## [1] "Color palettes: jungle"

![](introductory_files/figure-gfm/colors_exp-13.png)<!-- -->

    ## [1] "Color palettes: klimt"

![](introductory_files/figure-gfm/colors_exp-14.png)<!-- -->

    ## [1] "Color palettes: kpd"

![](introductory_files/figure-gfm/colors_exp-15.png)<!-- -->

    ## [1] "Color palettes: lava"

![](introductory_files/figure-gfm/colors_exp-16.png)<!-- -->

    ## [1] "Color palettes: origami"

![](introductory_files/figure-gfm/colors_exp-17.png)<!-- -->

    ## [1] "Color palettes: mixer1"

![](introductory_files/figure-gfm/colors_exp-18.png)<!-- -->

    ## [1] "Color palettes: mixer2"

![](introductory_files/figure-gfm/colors_exp-19.png)<!-- -->

    ## [1] "Color palettes: mixer3"

![](introductory_files/figure-gfm/colors_exp-20.png)<!-- -->

    ## [1] "Color palettes: mixer4"

![](introductory_files/figure-gfm/colors_exp-21.png)<!-- -->

    ## [1] "Color palettes: nature"

![](introductory_files/figure-gfm/colors_exp-22.png)<!-- -->

    ## [1] "Color palettes: neon1"

![](introductory_files/figure-gfm/colors_exp-23.png)<!-- -->

    ## [1] "Color palettes: neon2"

![](introductory_files/figure-gfm/colors_exp-24.png)<!-- -->

    ## [1] "Color palettes: retro1"

![](introductory_files/figure-gfm/colors_exp-25.png)<!-- -->

    ## [1] "Color palettes: retro2"

![](introductory_files/figure-gfm/colors_exp-26.png)<!-- -->

    ## [1] "Color palettes: retro3"

![](introductory_files/figure-gfm/colors_exp-27.png)<!-- -->

    ## [1] "Color palettes: retro4"

![](introductory_files/figure-gfm/colors_exp-28.png)<!-- -->

    ## [1] "Color palettes: sooph"

![](introductory_files/figure-gfm/colors_exp-29.png)<!-- -->

    ## [1] "Color palettes: sky"

![](introductory_files/figure-gfm/colors_exp-30.png)<!-- -->

    ## [1] "Color palettes: tuscany1"

![](introductory_files/figure-gfm/colors_exp-31.png)<!-- -->

    ## [1] "Color palettes: tuscany2"

![](introductory_files/figure-gfm/colors_exp-32.png)<!-- -->

    ## [1] "Color palettes: tuscany3"

![](introductory_files/figure-gfm/colors_exp-33.png)<!-- -->

    ## [1] "Color palettes: vrolik1"

![](introductory_files/figure-gfm/colors_exp-34.png)<!-- -->

    ## [1] "Color palettes: vrolik2"

![](introductory_files/figure-gfm/colors_exp-35.png)<!-- -->

    ## [1] "Color palettes: vrolik3"

![](introductory_files/figure-gfm/colors_exp-36.png)<!-- -->

    ## [1] "Color palettes: vrolik4"

![](introductory_files/figure-gfm/colors_exp-37.png)<!-- -->

    ## [1] "Color palettes: vrolik5"

![](introductory_files/figure-gfm/colors_exp-38.png)<!-- -->
