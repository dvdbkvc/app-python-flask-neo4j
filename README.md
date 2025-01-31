# Building Neo4j Applications with Python

> Learn how to interact with Neo4j from Python using the Neo4j Python Driver

This repository accompanies the [Building Neo4j Applications with Python course](https://graphacademy.neo4j.com/courses/app-python/) on [Neo4j GraphAcademy](https://graphacademy.neo4j.com/).

For a complete walkthrough of this repository, [enroll now](https://graphacademy.neo4j.com/courses/app-python/).

## A Note on comments

You may spot a number of comments in this repository that look a little like this:

```
# tag::something[]
someCode()
# end::something[]
```

We use [Asciidoc](https://asciidoc-py.github.io/index.html) to author our courses.
Using these tags means that we can use a macro to include portions of code directly into the course itself.

From the point of view of the course, you can go ahead and ignore them.

## Setting up the project
```
$ cd <project-parent>
$ git clone git@github.com:dvdbkvc/app-python-flask-neo4j.git
```

## Setting up the virtual evironment
```
$ cd ./app-python-flask-neo4j
$ python -m venv neoflix
$ source neoflix/bin/activate
(neoflix) $
```

## Installing required packages
```
(neoflix) $ pip install --requirement requirements.txt
```

## Running the application
```
(neoflix) $ export FLASK_APP=api
(neoflix) $ export FLASK_ENV=development
(neoflix) $ flask run
```
