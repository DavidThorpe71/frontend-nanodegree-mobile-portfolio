## Website Performance Optimization portfolio project

To open the fully optimized portfolio project please open the [index.html](dist/index.html) located in the in the [dist folder](/dist/)

The [app folder](/app/) contains the original versions (before I ran the Gulp tasks).


####Part 1: Optimize PageSpeed Insights score for index.html

For this page I used the Gulp task runner, using the included [gulp file](gulpfile.js).

First I installed node.js,
after this in the node.js command line I install the gulp command using

''npm install --global gulp-cli''

Then I installed gulp in your devDependencies using the below: 

''npm install --save-dev gulp''

Then using the included Gulp file I ran the gulp command to run all the tasks in the gulp file.

####Part 2: Optimize Frames per Second in pizza.html

In order to optimize the fps to at least 60fps I factored out randomPizzas and fixed the forced synchronised layouts that were being caused by this section.

