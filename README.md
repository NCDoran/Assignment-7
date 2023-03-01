# Assignment-7

## wesanderson
The wesanderson package has color palettes based on Wes Anderson films. It is on both GitHub and CRAN. 

To install:
```{r}
install.packages("wesanderson")
```

The package does have a vignette but it is not very complete. The most helpful way to learn about applications of this package are on the Github repo:  https://github.com/karthik/wesanderson

In the description it has the functions needed to see the palette names and see the different palettes. One of the applications it mentions is the Zissou1 palette (inspired by the Life Aquatic with Steve Zissou) is good for creating heat maps. The end of the description also has a list of examples of this palette being used in publications. There are more applications of it on R bloggers: https://www.r-bloggers.com/2022/07/colorful-r-plots-with-wes-anderson-palettes-pirate-ships/

Most palettes have only 4 to 5 colors in them, but you can include an argument in the function wespalette() to create a continuous gradient to pull more colors from, which is demonstrated in examples in the description file. 

```{r}
names(wes_palettes)
```
My favorite palette is probably the Royal1 palette inspired by the Royal Tenenbaums. I've used this palette as inspiration for posters and powerpoint presentations because I like the gradient of warm colors with the blue accent color. Taking the red from Ben Stiller's tracksuit is a nice touch. 
```{r}
wes_palette("Royal1")
```
#Review
I'm not familiar with many different R packages so I thought this would be a fun one to highlight after the lecture we had on graphic design and color palettes. As a film nerd I always really liked how color is used in Wes Anderson films and these palettes capture the aesthetics of some of my favorite movies, so that's fun. It doesn't look like the newest film French Dispatch has been added, so I would like to see that because one of the skits has a nice color palette of pink, blue, and yellow that aren't as pastel-like as the Moonrise Kingdom palette with similar colors. 
```{r}
wes_palette("Moonrise3")
```
I don't really have anything else to say, they're color palettes. They are easy to use in both base R and ggplot, many are color-blind friendly. It's just fun to have cultural references in data science. 
