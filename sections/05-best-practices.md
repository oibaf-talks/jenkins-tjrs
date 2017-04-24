# [Melhores práticas][1]

* Always secure Jenkins
* In larger systems, don't build on the master
* Backup Jenkins Home regularly
* Limit project names to a sane (e.g. alphanumeric) character set
* Use "file fingerprinting" to manage dependencies


# Melhores práticas (cont.)

* The most reliable builds will be clean builds, which are built fully from Source Code Control
* Integrate tightly with your issue tracking system, like JIRA or bugzilla, to reduce the need for maintaining a Change Log
* Integrate tightly with a repository browsing tool like FishEye if you are using Subversion as source code management tool
* Always configure your job to generate trend reports and automated testing when running a Java build
* Set up Jenkins on the partition that has the most free disk-space


# Melhores práticas (cont.)

* Archive unused jobs before removing them
* Setup a different job/project for each maintenance or development branch you create
* Prevent resource collisions in jobs that are running in parallel
* Avoid scheduling all jobs to start at the same time
* Set up email notifications mapping to ALL developers in the project, so that everyone on the team has his pulse on the project's current status


# Melhores práticas (cont.)

* Take steps to ensure failures are reported as soon as possible
* Write jobs for your maintenance tasks, such as cleanup operations to avoid full disk problems
* Tag, label, or baseline the codebase after the successful build

[1]:https://wiki.jenkins-ci.org/display/JENKINS/Jenkins+Best+Practices

