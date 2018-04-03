# Git & GitHub

Git & GitHub are important, that's all I know for now. When I learn more I'll update this description.

___

* [Conflict when pulling - 3/4/18](https://github.com/elewa-academy/study-journal-template/blob/master/02-04__08-04/03-04-2018.md)
* [Pull requests - 9/4/18](https://github.com/elewa-academy/study-journal-template/blob/master/09-04__15-04/09-04-2018.md)
* [Unstaging a file - 15/4/18](https://github.com/elewa-academy/study-journal-template/blob/master/09-04__15-04/15-04-2018.md)
___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>

____________________________________

# Gitbook

- a command line application (may be used to build Git pages)
- takes everything in markdown, converts to html and serves it
- reads from file "Summary.md" to build the menu
- has a specific format/html template (may be modified but... why...?)
- doc folder is where the build (with converted htmls) are stored

# Commands

- [Git commands](./concepts/CommandLine.md#Git)

# Git

- language that works underlying in your computer folder structure. It decides there, in the OS, in which branch you are

*  Merging:
- will add the branch you want to merge (pull) into the current branch
- will detect conflicts and warn about them: a conflict means two different pieces of content in the same file in the SAME LINE (different content in different lines of the same file are not conflicts!)
- command = Git merge name-of-branch-being-pulled-into-current
- merge conflicts will be 'logged'/saved in the commit three