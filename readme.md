BikePDX
=======

By Micah Courey, 25-Oct-2015

A website with a map, information, photos and reviews on Bike Routes in Portland, OR. Check it out at http://micahcourey.github.io/BikePDX

Setup
----------
* Clone repository,
```bash
git clone https://github.com/micahcourey/BikePDX.git
```
* Change directory.
```bash
cd app
```
* Install the dependencies. If you're running Mac OS or Linux, you may need to run `sudo npm install`    instead, depending on how your machine is configured.
```bash
npm install
bower install
```
* Run:
```bash
npm start
```

This will compile the Sass and assemble your Angular app. **Now go to `localhost:8080` in your browser to see it in action.** When you change any file in the `client` folder, the appropriate Gulp task will run to build new files.

* To run the compiling process once, without watching any files, use the `build` command.
```bash
npm start build
```

Technologies Used
----------
JavaScript, HTML, CSS, AngularJS, Node.js, Sass, Foundation

License
----------
MIT License, Copyright (c) 2015 Micah Courey
