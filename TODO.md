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
    dottle pull [repo] -- updates the topic repo
    dottle modified -- shows which repos/topics have local modifications
    dottle diff [repo]/[topic] -- shows a diff of local changes for a repo
    dottle open [repo]/[topic] -- open the repo and/or topic in an editor

