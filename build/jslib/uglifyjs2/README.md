Sets up uglifyjs2 for use in the optimizer.

Current embedded version: 2.4.16, source-map 0.1.34

Steps:

    ./generate.sh

Then update this file with the uglifyjs2 version fetched.

* UPDATE VERSION NUMBERS IN X.JS
* Confirm the `raw` array in combine.js is correct.

THINGS TO CHECK:

* Compare node_modules/uglify-js2/tools/node.js and what
  is put in last part of the combined file.
