# microwave-jvm
Microwave MVC provides basic, cross-platform-compatible templates for different tech stacks so you can quickly get started with web development.

#### What you get out of this Microwave
* Java 7
* IntelliJ IDEA Community Edition
* Postgres
* Ubuntu 14.04 Vagrant Box
* provisioned using Chef / Test Kitchen / Berkshelf

#### Dependencies
* Virtualbox
* Vagrant
* ChefDK

## 1-Minute JVM Environment
    $ vagrant install plugin vagrant-berkshelf
    $ cd workspace
    $ vagrant up                          # provisions the box for the first time
    $ vagrant halt && vagrant destroy     # this will allow ubuntu-desktop to load
    * Log in with user vagrant and password vagrant
    * Open terminal inside ubuntu
    $ idea-IC-14.1.1/bin/idea.sh 
    * Follow the instructions to configure IntelliJ for the first time
