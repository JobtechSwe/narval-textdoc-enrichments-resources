# narval-textdoc-enrichments-resources
Empty git-repo for creating openshift fileserver. Do NOT check in any files here, please.

------------------------------
DESCRIPTION
=============
Git-repo for openshift fileserver hosting ML-models. 

This repo uses LFS since the model files are quite large.


Install LFS, instructions
---------------------------
https://help.github.com/articles/installing-git-large-file-storage/

Configuring LFS
---------------
https://help.github.com/articles/configuring-git-large-file-storage/

Configure LFS-tracking for resources-folder
-----------------------------------------
git lfs track /resources/prediction_models/**
git lfs track /resources/wordembedding_models/**

LFS Tutorial
------------
https://github.com/git-lfs/git-lfs/wiki/Tutorial





