My dotfiles project.  
Seems to be the hot thing to do these days.  Perl based.  May be interesting, may be useless.  Who knows.<br>
**Warning:** This will currently blow away any file that is in the way.  (currently zsh  dot-files and a .zprezto directory)

Required Perl Modules:
 - YAML::Any  (used for config file parsing)

HOWTO/Usage/Notes
-----
 - *assumes you're already using zsh*
 - Clone this project
 - Backup your important dotfiles (issue #3 tracks this)
 - Verify the configuration
     - The source directory is typically __HOME__/.dotfiles  it is where this repo gets copied during install.
     - The target is deleted prior to the action taking place (symlink or copy) **no backups are made**
 - Run the provided install script
 - Logout/login


Submodules
----------
I recommend changing the submodules to point to your own forks of ohmyzsh or prezto (or your own zsh scripts etc) modify the
dotfiles.conf as needed
 - [my fork of prezto](https://github.com/skarfacegc/prezto).  sorin's execellent zsh environment. https://github.com/sorin-ionescu/prezto
 


Roadmap
-------
See [issues](https://github.com/skarfacegc/dotfiles/issues) and [milestones](https://github.com/skarfacegc/dotfiles/issues/milestones) for current worklist  
(going to track everything with ~~bugs~~ I mean _issues_)



Fork this, modify to fit your needs, submit a pull request for anything others might find useful
