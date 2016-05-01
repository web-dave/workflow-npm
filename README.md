# workflow npm.

## Install
required :
- node
- git

Run `npm i` to install

## tasks
`npm start`
start workflow:
<ol>
<li>run prestart:
<ol>
 <li>run wiresrc</li>
 <li>run wiredep</li>
 </ol></li>
<li>run lite</li>
<li>run watch:scss</li>
</ol>

## scripts
You can run every script from bash `$npm run {scriptName}`

`lite`
start lite-server, a little browsersync based server by John Papa

`wiresrc`
inject your source into index.html

`wiredep`
inject bower source into index.html

`watch:scss`
start scss workflow (run node-sass in watchmode: watch and compile on change)



