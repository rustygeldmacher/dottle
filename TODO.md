* Use .sh extension for scripts (init, install, etc.)
* A "verbose" or "debug" mode
* Ideal usage:
    dottle list -- lists all available topics
    dottle using -- lists all used topics
    dottle check -- checks for proper system requirements
    dottle clone [repo] -- Adds a topic repo
    dottle use [repo]/[topic] -- Enables a topic from a repo
      If no topic is given, all topics from the repo are used
    dottle remove [repo]/[topic] -- stops using the topic
      If no topic is given, all topics from the repo are removed
    dottle pull [repo] -- updates the topic repo
    dottle diff [repo]/[topic] -- shows a diff of local changes for a repo
    dottle open [repo]/[topic] -- open the repo and/or topic in an editor

