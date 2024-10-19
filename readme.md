# Ultrafiche

Convert pdf files into standalone html files with embedded svg
images. Just like its namesake, this program renders the pages of a
common document format onto a rather questionable medium. And not at all
unlike the photographic films used for ultrafiche archiving, which went
from representing the bleeding edge of technological innovation to being
an outdated relic of the past within a matter of only a few years, the
html-cum-svg renderings produced by this script can hardly be expected
to stand the test of time. Furthermore, the svg renderings produced
by pdf2svg are essentially just drawings of written text, which pretty
much breaks all useful benefits of using digital document formats in the
first place, such as keyword search or improved accessibility. Still,
if you need to create a digital facsimile of some pdf that is rendered
predictably and efficiently by the default web browser installed on
modern cellphones, this script could possibly be of use to you.

## Usage

```bash
ultrafiche <INPUT-FILE> <OUTPUT-FILE>
```

## Dependencies

* pdf2svg
