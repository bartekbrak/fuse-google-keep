# fuse-google-keep
Mount Google Keep as Virtual FileSystem using fuse. 

**Goal**: edit portable notes locally using your favourite EDITOR. 

### Plan
- [ ] implement most basic RO system
- [ ] include end to end scenarios, maybe including Selenium, for
  - [ ] sync on save
  - [ ] new note appears locally
  - [ ] desktop notification when new note appers
  - [ ] merging remote and local changes, (what algorithm to use for merging, how to handle conflicts)
- [ ] implement end to end scenarios
- [ ] write down bolierplate for a GitHub project, collaboration, issues template, CI
- [ ] write down the plan for promoting the library and getting the feedback from the users

Inspiration:
- https://github.com/fusepy/fusepy
- https://github.com/jcline/fuse-google-drive
- https://en.wikipedia.org/wiki/Filesystem_in_Userspace
- https://www.stavros.io/posts/python-fuse-filesystem/
- https://github.com/skorokithakis/python-fuse-sample
- https://github.com/kiwiz/gkeepapi
- https://github.com/Nekmo/gkeep

www: https://grupabrak.github.io/fuse-google-keep/
