# Static exports of Science in the Making content

This isn't quite a gh-pages archive just yet. The Canvas Images still point to the shared DLCS instance, with their image services.
However, each canvas is accompanied by a static JPEG, but it's linked via a `seeAlso`.

The links between manifests, annotation pages and these static images are also _relative_: `"@id": "./xxx"` 

So before it can be fully static these need to be patched up and given absolute URLs, and the image resources need to be replaced with the static versions. All the data is here.

These IIIF resources are extracted using [iiif_downloader.py](https://github.com/digirati-co-uk/rs-services/blob/winston-preview/app/iiif_downloader.py).
You need to run [annocounter.py](https://github.com/digirati-co-uk/rs-services/blob/winston-preview/app/annocounter.py) to generate the source JSON files first (they are also the sources for the CSV report).

The above links are not a public repo.
