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

*Goods*
Do everything you need: get pretty json files describing your sketch project.

*Bads*
When committing on the project, you have no idea of the json files that are part
of the commit.

git sketch plugin
-----------------

Check [git-sketch-plugin](https://github.com/mathieudutour/git-sketch-plugin)
If I understand correctly it is the ancestor of Kaktus.

*Goods*
You can do the commit and push from Sketch !!!

*Bads*
Not sure the plugin is even generating json files out of the sketch project.
