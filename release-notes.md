# Git Town Release Notes

## 0.3
* multi-user support for feature branches (https://github.com/Originate/git-town/issues/35)
* git sync-fork
* <a href="http://cukes.info" target="_blank">Cucumber</a> feature specs (you need Ruby 2.x)
* much faster testing thanks to completely local test Git repos (https://github.com/Originate/git-town/issues/25)
* stores configuration in the Git configuration instead of a dedicated file
* always cleans up abort and continue scripts after using one of them
* only makes one fetch from the central repo per session
* automatically prunes remote branches when fetching updates
* simpler readme, dedicated RDD document


## 0.2.2
* fixes "unary" error messages
* lots of output and documentation improvements


## 0.2.1
* better terminal output
* Travis CI improvements
* better documentation


## 0.2
* displays the duration of specs
* only pulls the main branch if it has a remote
* --abort options to abort failed Git Town operations
* --continue options to continue some Git Town operations after fixing the underlying issues
* can be installed through Homebrew
* colored test output
* display summary after tests
* exit with proper status codes
* better documentation


## 0.1
* git hack, git sync, git extract, git ship, git kill
* basic test framework
* Travis CI integration
* self-hosting: uses Git Town for Git Town development
