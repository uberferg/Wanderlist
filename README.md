###############################################################################
# Wanderlist
#
# Track where you've been, look where you're going, see where you'll go.
#
# . . . Or something like that.
###############################################################################

This project uses Djano v1.8.2. Frontend is, as it stands, built atop Sass,
Susy/Breakpoint, and the Grunt.js workflow manager, with CoffeeScript, linting,
and minification all enabled by default. LiveReload is currently DISABLED. This
is easy to fix, and I'll get to it soon.

###############################################################################
# SETUP
###############################################################################

To get that front-end stuff working as it should, hop on over to the 
wanderlist/templates directory and run:

npm install

. . . Then try:

grunt

. . . And all should be good to go.

N.b.: If your environment is set up properly, you shouldn't need to run 
sudo npm install. It so happens mine is not set up properly at the moment,
so I went ahead and did this. I'll get virtual environment stuff set up a bit
later; my pip installation is currently broken, so I'll have to fix that first.
