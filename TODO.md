* Use .sh extension for scripts (init, install, etc.)
* A "verbose" or "debug" mode
* Ideal usage:
    dottle list -- lists all topics
      dottle list using -- list topics being used
      dottle list available -- list topics not being used
    dottle check -- checks for proper system requirements
    dottle clone [repo] -- Adds a topic repo
    dottle use [repo]/[topic] -- Enables a topic from a repo
      If no topic is given, all topics from the repo are used
    dottle remove [repo]/[topic] -- stops using the topic
      If no topic is given, all topics from the repo are removed
    dottle update [repo] -- updates the topic repo
      dottle update dottle -- updates dottle itself
    dottle status -- shows which repos/topics have local modifications
    dottle diff [repo]/[topic] -- shows a diff of local changes for a repo
    dottle open [repo]/[topic] -- open the repo and/or topic in an editor
    dottle cd [repo]/[topic] -- change to the directory of the topic or repo

* Add 'dottle cd'
* Add installation script
* Add 'dottle new' to create a new repository or topic
* Add 'dottle config' for getting config values
* init topic after using
* list topics in repo after cloning

