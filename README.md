Easy rake task that will simplify up mount process of your
[truecrypt](http://www.truecrypt.org/) encrypted files.

## Set up

* git clone project
* *cd ~/Documents/path_wher_i_cloned_this_project/*
* *cp ./paths_example.rb ./paths.rb*
* edit your *paths.rb* file
  * !!! don't forget to create your MOUNT_FOLDER and BACKUP_FOLDER !!!


## Bash alias

After everything is set up, in your *~/.bashrc* or *~/.bash_profile* you can do something like
this

    alias quickreed='cd ~/Documents/path_wher_i_cloned_this_project/; rake mount; vim ~/Documents/mount_crypt_here/seecret_file; rake umount;'

reload your bash terminal, and next time you do...

     quickreed

...you'll mount your truecrypt file, edit file in vim, and unmount truecrypt file once you close vim.

## Links

http://www.truecrypt.org/
