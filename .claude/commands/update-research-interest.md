# Update Research Interest Image

Replace the research interest diagram image on the homepage.

## Usage

```
/update-research-interest <image-path>
```

**Argument:** `$ARGUMENTS` — full path to the new image file (PNG/JPG/SVG)

## Steps

1. Copy the file at `$ARGUMENTS` to `E:/Jasper0122.github.io/assets/images/photos/interst.png`, overwriting the existing file.
2. Confirm the copy succeeded by checking the file exists.
3. Tell the user the image has been replaced and remind them to run `bundle exec jekyll serve` to preview locally (or refresh the browser if already running).

If no argument is provided, tell the user to provide the full path to the new image, e.g.:
```
/update-research-interest C:/Users/zongr/Downloads/my_new_diagram.png
```
