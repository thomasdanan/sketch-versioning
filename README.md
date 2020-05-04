Sketch Versioning
=================

.sketch file is actually a zip file containing a json representation of the
project.

git hooks method
----------------

Check [git hook method and scripts](https://medium.com/cloudaper/simple-git-versioning-for-sketch-5d77df01571e).
After downloading few scripts in your repo, we can commit changes on the
.sketch file, and the hook scripts will unzip the sketch, prettify the json
and prepare the commit.
