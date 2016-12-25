# Why use git to manage soures.list.d/yum.repose.d?
### Iorder to install some special software by using apt,
### the non-univerral source was been add to the soures.list.d/yum.repoes.d, once we install the special software well, we won't hope to upgrade the one by apt; 
### In other hand, when we run the "apt update" command, the non-universal source.list will be check even fetch again, 
###it will waste time, even output some usefulless information.
### So it is necessary to use git to manage the sources.list.d/yum.repoes.d.
### So now, I try to do this.
# Practice
### In practice, it seams that every time one run the command "apt/apt-get/apt-fast/ect.", the sources.list.d/yum.repoes.d folder will be read;
### So, maybe in some case, we would better to use 'git checkout' to the suitable git branch and commit status.
