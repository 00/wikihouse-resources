Repo for binary / large files used by the [Wiki House] platform.  To use it with
https://github.com/tav/togethr/blob/master/assetgen.yaml you need:

* an $AMPIFY_ROOT environment variable resolving to a directory
* a directory inside that called `third_party`

Clone this repo into the `third_party` folder as `wikihouse-resources` and add 
resources with lines like:

    - %(AMPIFY_ROOT)s/third_party/wikihouse-resources/gfx/foo.png

[Wiki House]: http://github.com/thruflo/wikihouse
