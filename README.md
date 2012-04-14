# Build node.js on cloudbees

The jenkins servers on cloudbees don't include a version of node js.
This project builds a node.js distribute for use on node.js.

To build simply add this project using janky. Janky will call cibuild
which will download and build node.js from source.

After the build is done, store the tar file somewhere publically
accessible so that it be downloaded for other builds.
