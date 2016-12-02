# blueprint

This repo. contains Diagrams, schemes, technical drawings etc.
of some of my personal projects.

## linking

You can use `http://blueprint.lent.ink/year/nmbr`
which will redirect to the right location
(e.g. `https://cdn.lent.ink/blueprint/2016/1337/img.png`).

## Metadata

While not used atm.
I committed myself to provide metadata.

```javascript
{
	"description": "Mandatory description of the picture",
	"projectURL": "http://optionally.url/post-to-something",
	"editWith": ["url01ofSoftwareThatCanOpenTheOriginal", "urlToSecondProgram", "etc."]
}
```

Every directory should contain a file called metadata.json

## File structure

The directories are numbered by year.
Every image has a number in that year.
This gives us `/2016/1337/`.
Inside the folder, we have the image (PNG!),
the original, which is editable (in case of draw.io, the PNG itself is editable)
and the metadata.

+ `/2016/1337/img.png`
+ `/2016/1337/metadata.json`
