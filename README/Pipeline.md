#Pipeline description
### we built our pipeline using circleci
## pipline process
### this pipeline contains the following orbs
#### - node
#### - aws
### - eb
#### these configurations are necessary to run the next commands

### this pipline contains two main jobs
#### - build app
#### - deploy app

### workflow
#### - first run build
#### - then wait for approval
#### - finally deploy