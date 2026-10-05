# interactor-space-starvector-8b-im2svg

A model-serving container that turns a raster image into SVG markup with an image-to-SVG language model.

## What it is for

The predictor loads the `starvector/starvector-8b-im2svg` checkpoint on a GPU and returns the SVG it generates for an input image.

## Building and running

```sh
cog predict -i image_path=@input.png
```

That builds the container and runs the predictor on `input.png`.

## Licence

Apache-2.0. See [LICENSE](LICENSE). The model weights carry their own licence.
