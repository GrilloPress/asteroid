# Things I've learnt

## Meteor run

To create a project with meteor run:

```
meteor create {{project_name}}
```

This will create the following files

```
/client
  main.css
  main.html
  main.js
/server
  main.js
.gitignore
package.json
```

The front-end files are placed into the client folder and the backend is inside the server folder.

## Meteor NPM

To install your dependencies listed in your ```package.json``` file you run:

```
meteor npm install
```

## Run your meteor app

To run your meteor app you execute the following:

```
meteor run
```

first time you do this, it compiles everything and downloads packages so this takes a while...

## The import folder

Meteor now suggests placing much of your app inside a ```imports``` folder.

Things like the ```ui```, ```api``` etc. which you then include into your client or server code.