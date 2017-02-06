# dropzone from dropzonejs.com

this is a repo to hold different versions of dropzone you may need 
and also to make them available for the toolbax application as default

# dropzone ready to run files
Downloaded from dropzone.com and set to the "packages" branch the versions you prefer for the toolbox as default

Checkout the single version (branch) you need or 
create a new branch starting at the master branch and add you version as follow
    git co master
    git co -b myNewVersion (eg. v3-1-2; branches with slashes, folders with dots)
    mkdir ./v3.1.2/
and put you files here ./v3.1.2/*

The master branch should only contain the README to guide developers, the "packages" 
branch contains all versions to be used. (old and new once). 
The versions branches to modify for bug or improvements or to use just as single branch 
for other projects.

if you need them toolbox wide? then merge your version to the "packages" branch
NEVER to the master!

example:
# packages branch
./v1.8.3/_some_files_of_version_1.8.3
./v2.0.0-Beta/_some_files_of_version_v2.0.0-Beta
./README.txt <- this readme

