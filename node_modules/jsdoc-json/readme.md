# jsdoc-json

A JSDoc template that generates JSON output (instead of HTML).

## install

    npm install jsdoc-json

## use

    jsdoc --template ./node_modules/jsdoc-json --destination doc.json --recurse src

Provide the path to the output file with the `destination` option (parent directory must exist).  Note that as of JSDoc v3.5, you need to provide the path to the template directory (instead of specifying the package name).
