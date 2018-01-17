# Yes, I know this is not a blog, but Thats what I use it for
## So I have a problem that i need to run a large number of experiments with
* Experiments require source code control -- that was easy git...
* Experiments require reproducibility -- Sumatra to the rescue. 
** It uses git. SQLite, and Django to help track.
** It tracks input files, output files and parameters 
** Problem: I am going to be using very large files. git is very bad at that
** git-annex, git-annex-assistant to the rescue?

--------
## git-annex notes
* http://git-annex.branchable.com/tips/largefiles/ -- looks like what I need to mix things

## Installing a recent version of git-annex seems to need to have support of the neuroscience groups.
* sumatra is supported with neuroscience, but 
* git-annex is directly supported. 
** go to 
* http://neuro.debian.net/pkgs/git-annex-standalone.html#binary-pkg-git-annex-standalone
* select [Install]
* select Version -- I am using LTS-16.04
** 
<code>
wget -O- http://neuro.debian.net/lists/xenial.us-nh.full | sudo tee /etc/apt/sources.list.d/neurodebian.sources.list

sudo apt-key adv --recv-keys --keyserver hkp://pool.sks-keyservers.net:80 0xA5D32F012649A5A9

sudo apt-get update

sudo apt-get install git-annex-standalone

</code>
