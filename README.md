# CS103a PA03
[Movie Link](https://drive.google.com/file/d/1vL-UFwvIagKvPcBXZoVqbigMJs_w0XSF/view?usp=sharing)
This application is a course search application for courses at Brandeis University. It was implemented from the base application found [here](https://github.com/tjhickey724/cs103aExpressApp/tree/pa03). It has been extended such that it now upserts the DB with an array of `String` times, and a new course search form/route that searches by name (using a regex query). Lastly, it has been updated to use a flexbox display instead of an `ol` list to display the resulting courses from a query.
## Where to Download From?

to download this code, run the following command:

```bash
git clone git@github.com:sbrenner132/cosi103a-pa03.git
```

N.B. you must login with your SSH passphrase

## Installation

cd into the folder

Install the packages with
``` bash
npm install
```
Start the project with
``` bash
node app.js
```
or install nodemon (the node monitoring app) with
``` bash
npm install -g nodemon
```
and start the project with
``` bash
nodemon
```

