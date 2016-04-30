# workflow npm based at the moment windows only.

## Install
required :
- node
- git

Run `npm i` to install

## development

Run `npm start` for preview.

## Testing

Running `npm test` will run the unit tests with karma.

## build

Run `npm run build` to build resources. After that the resources are available at 
`./src/main/resources/static/`.

## review
run `npm run serve:build` to review the build.

<hr>

##important files

 - build-src.json
 - vendor-js-src.json
 - vendor-css-src.json
 
 add new files here for build process
 
 - replace-map.dev.json
 
 add new files herer to inject them into index.html at `npm start`
 
 - replace-map.dist.json
