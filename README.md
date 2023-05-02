# moose-framework-2023

Rebuilding the framework ... work ongoing ... React + Gulp + SCSS + WP + Composer + ACF Pro etc. The last
one was not working with anything later than Node.js 14x due to node-sass. Node-sass was necessary cuz
gulp-sass was using it. Now replaced that with gulp-dart-sass and removed the old stuff. Also removed
bower-components/bootstrap. Replaced with Bootstrap v4.6.1 and updated global.scss with the node version
instead. Gulp watch is now working under Node.js 18.15.0 which is the latest. We should be good for a while.
