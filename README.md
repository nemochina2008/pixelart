# Package pixelart

R Package to make Pixel Art models. [[Blog post introducing the package]](https://privefl.github.io/blog/shiny-app-for-making-pixel-art-models/)

```r
# Installation
devtools::install_github("privefl/pixelart")

# Run Shiny App
pixelart::run_app()
```

Webshot of Shiny App:

<center><img src="webshot.png" style="width:70%;"></center>

## Example

I present you Kong. **A.** Picture of Kong. **B.** Kong as a pixel art model, created with R package pixelart. **C. & D.** Two pixel art drawings of Kong, based on A & B.

<center><img src="kongs.png" style="width:70%;"></center>

## News

- March 10, 2018: run kmeans in the Lab space (instead of the RGB space)

- Nov 18, 2017: added some options for croping, rotating and saturating the image

## To improve

I think there is room for improving the pixel art models (e.g. better separation of colors). Maybe with [package imager](https://cran.r-project.org/web/packages/imager/vignettes/pixsets.html). Ideas are welcome.
