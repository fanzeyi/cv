# cv

This is a cv template I wrote and designed for myself. I decided I will open
source it once I got an internship offer. So here it is.

You can preview it [here](./cv.pdf).

## Font

This template uses [Raleway](https://github.com/impallari/Raleway) as main font.
They are also open source!

## Build

Use latexmk:

    latexmk -xelatex

## Notes

If you want to add metadata to the generated PDF file, uncomment line 29-31 and
comment line 32 (I added this for "SEO" reason but I suspect it actually works)

There is also an optional tagline at line 145 for you to enable.

You would also need to adjust the number at line 199 because I didn't figure out
a way to make LaTeX automatically adjust the position of the right part.

## License

LaTeX Project Public License 1.3c
