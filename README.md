# CHAOSS
![CHAOSS](https://github.com/Prabhat-IIT/CHAOSS-Microtasks/blob/master/GraphsAndTables/Chaoss_Logo.png)

# Microtasks

## Requirements:

1. Basic python development environment : virtualenv, [python 3](https://www.python.org/downloads/), pip3.
2. [GrimoireLab packages](http://grimoirelab.github.io/), ElasticSearch and mariaDB.
3. [Elasticsearch](http://elasticsearch-py.readthedocs.io/en/master/index.html) should be running on localhost:9200
4. [Kibana](https://www.elastic.co/products/kibana) can also be used in order to visualize data in better way.

## Problem Statement

### Microtask 1:
Produce a listing of the number of new committers per month, and the number of commits for each of them, as a table and as a CSV file. Use the GrimoireLab enriched index for git.

#### New Committers per month
![Committers table](https://github.com/Prabhat-IIT/CHAOSS-Microtasks/blob/master/GraphsAndTables/NewCommitters.png)

#### Number of commits
![Number of commits](https://github.com/Prabhat-IIT/CHAOSS-Microtasks/blob/master/GraphsAndTables/NumberOfCommit.png)

### Microtask 2:
Produce a chart showing the distribution of time-to-close (using the corresponding field in the GrimoireLab enriched index for GitHub issues) for issues already closed, and opened during the last six months.
![plot](https://github.com/Prabhat-IIT/CHAOSS-Microtasks/blob/master/GraphsAndTables/Microtask2.png)


### Microtask 3:
Produce a listing of repositories, as a table and as CSV file, with the number of commits authored, issues opened, and pull requests opened, during the last three months, ordered by the total number (commits plus issues plus pull requests).
![Popular repo plot](https://github.com/Prabhat-IIT/CHAOSS-Microtasks/blob/master/GraphsAndTables/Repo_Total.png)


### Microtask 4:
Perform any other analysis you may find interesting, based on GrimoireLab enriched indexes for git and GitHub repositories.

I've implemented a basic fork metric to show how github api can be used to support metric that are not yet supported by grimoirelab.
#### Number of Forks
![Forks](https://github.com/Prabhat-IIT/CHAOSS-Microtasks/blob/master/GraphsAndTables/NumberOfForks.png)

### Microtask 5:
Produce a pull request for any of the GrimoireLab tools, and try to follow instructions until it gets accepted. Try do do something simple that you consider useful, not necessarily fix to the code: improvement of comments, documentation or testing will usually be easier to get accepted, and very useful for the project. Please, avoid just producing a random pull request just to have another microtask: the objective is not that you get one more microtask done, but that you understand how to interact with developers in the project contributing with something that could be useful).

For this microtask, I produced 3 pull requests:

Pull request1 : In this pull request I added the support for Default name in report produced by manuscripts.

[Pull request 1](https://github.com/chaoss/grimoirelab-manuscripts/pull/33)

Pull request2: In this pull request I removed a bug in manuscripts which causes the directory of data and figures generated automatically by manuscripts to get recursively copied.

[Pull request 2](https://github.com/chaoss/grimoirelab-manuscripts/pull/35)

Pull request3: In this pull request I fixed a broken link in grimoirelab tutorial( although it was little bit complex than broken link)

[Pull request 3](https://github.com/chaoss/grimoirelab-tutorial/pull/16)

Pull request4: In this pull request I added the support for Co-author commits in Github to grimoirelab-elk

[Pull request 4](https://github.com/chaoss/grimoirelab-elk/pull/289)

Pull request5: In this pull request minor changes in Perceval gerrit backend is done

[Pull request 5](https://github.com/chaoss/grimoirelab-perceval/pull/374)
