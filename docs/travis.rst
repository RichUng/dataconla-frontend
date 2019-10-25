Frontend CI/CD Pipeline
=======================

This website uses `Travis CI <https://travis-ci.org/>`_ for its Continuous Integration and Continuous Delivery (CI/CD) pipeline so that we can automate the build and deployment of the Data Con website when changes are pushed to the site repo's master branch.

Travis CI
---------

Travis CI uses a `.travis.yml file <https://github.com/RichUng/dataconla-frontend/blob/master/.travis.yml>`_ located within the root directory of the repository to configure the automated integration and deployment. Travis CI will detect new commits made to the master branch, pull the latest commit, run the configuration specified within the .travis.yml file, and deploy the site to GitHub Pages.

CI/CD Tools
-----------

This project uses Travis CI because it's free for open source projects. However, if interested, below are other CI/CD tools that one can use for other projects:

- `Jenkins <https://jenkins.io/>`_
- AWS CI/CD Services
	- `CodePipeline <https://aws.amazon.com/codepipeline/>`_
	- `CodeBuild <https://aws.amazon.com/codebuild/>`_
	- `CodeDeploy <https://aws.amazon.com/codedeploy/>`_