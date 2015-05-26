# agave-mulligan
This is a first pass at the tech and tool bootstrapping around a reproducible experimental environment. 
This is mostly focused on science hackers and experimentalists since formal application development and 
wet-digital hybrid experimentation has its own best practices. 

## SETUP
* Create Github Account
* Fork deardooley/agave-mulligan

>         - .travis.ci
        - .dockerignore
        + assets
        + data
        - docker-compose.yml
        - discovery.yml
        + docs
        - index.ipynb
        - publish.sh
        + project
        - Dockerfile
        - AUTHORS.md
        - README.md
        - LICENSE
* Set up automatic build on docker hub
* Add static assets like images, etc to assets folder
* Update `AUTHORS.md` with your project members' names
* Update `LICENSE` if apprpriate
* Add code to project `directory`
        * Source
        * Tests
        * Build file
* Open Jupyter and update intro with your project info

## WORK
* Work out of Jupyter, or on your code. 
* Document process in notebook
* Save notebook and commit along with code.
* Branch for new ideas, directions, etc
* Set up `.travis.ci` to run tests for free
* Add default hello world test data to `data` dir

### COMMENT
* Gitter for conversations and communication logs
* Comment on releases and reference commits.

### RELEASE
* list any relevant external sources of data, apps, code, etc in the discovery.yml file
* Update docs to produce valid usage information for your app if appropriate
* Create a release of the project
* Update the resulting Docker build to match the release tag.

### SHARE
* Run `publish.sh` to register your container as an app for others to use
* Run `benchmark.sh` to benchmark your app using the sample data in the `data` folder and/or `discovery.yml` file.
* Add a "Try it yourself" button to your project readme.
