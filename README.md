# Security task list powered by TaskWarrior

Lists for:

- AWS security review    (IN PROGRESS)
- Google Cloud review    (IN PROGRESS)
- AIX host review        (IN PROGRESS)
- Linux host review      (IN PROGRESS)
- Windows host review    (IN PROGRESS)
- Web application review (IN PROGRESS)


# Installation

- install taskwarrior
- import security-tasklist.json 
- `hrv.*` => AIX, Linux, Windows host review
- `cloud.*` => AWS, GCloud, Azure(TODO)
- `web` => web application tasks


# Useful commands

```
task list
task projects
task proj:hrv 
task proj.is:hrv or proj:hrv.aix
```


# Roadmap

- add more to currently existings projects
- add more projects e.g. Azure, Android, AngularJS, Java, Wordpress, either using projects or via tags
- add tags to group certain entries
- add aliases for easier navigation of common stuff. e.g. AIX is all hrv and hrv.aix 
- research subtasks
- research adding links to external resources or markdown (check annotation)
- research reports formats
- research switching between multiple workspaces (maybe script to create a new worksptace and import tasklist)
- split tasklist per project if it makes sense
- model to add new stuff via pull request
	- convention for titles? tags? projects?
	- test and change current convention with projects if necessary
- research taskwarrior server and synchronizatin and multiple users editing tasks simultaneously 
- research assigning tasks
- research integrations
- research web client or any other web which can import tasks
- split tasks per technology if it makes sense and create aliases to easily import in bulk various tasks

