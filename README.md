# workflow npm.

I use scss, lite-server, bower

## Install
required :
- node
- git

### Run 
```
$ npm i
``` 


## tasks

### start development workflow:
```
$ npm start
``` 
### start build workflow:
```
$ npm run build
``` 


### Projectstructur:

```
app
    index.tpl.html
    app
        app.js
        components
            ...
        styles
    scss
        main.scss
        ...
bower.json
package.json
```

## scripts
You can run every script from bash 
```
$npm run {scriptName}
```

`lite`
start lite-server, a little browsersync based server by John Papa

`wiresrc:dev`
inject your source into index.html in development process

`wiredep`
inject bower source into index.html

`watch:scss`
start scss workflow (run node-sass in watchmode: watch and compile on change)

`bb`
concat bower source while build process

`start` 
start dev process
 
`uglify:js` 
concat and uglify your source while build process

`uglify:scss`
scss preproccesing while build process

`build`
start build process

`wiresrc:build` 
inject your source into index.html in build process

`clean`
clear dist
