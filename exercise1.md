Language picked is Python, that is the programming language that I have used most.

Some linting tools are Flake8 and Pylama which both combined multiple linters.

GeeksforGeeks gives top 10 Python testing frameworks: PyTest, PyUnit, Nose2,The Robot Framework, Behave, Testify, Lettuce, PyUnitReport, Mamba, Green.

Some building tools are Platformio Core, PyBuilder, Scons, Buildout and BitBake.

GeeksforGeeks list couple of CI/CD tools, like Travis CI, GitLab, Docker, TeamCity, Semaphore, Circle CI, Bamboo, Buddy, Azure DevOps Server, Bitrise, CodeShip, Spinnaker, Buildbot and Wrecker.

To make a decision on what kind of CI setup team should use, there are several factors. How large project is? Does it have special requirements? Are there multiple teams and projects that could use same CI setup? Does the team have expertise on configuring self-hosted setup?

For the team of six people, I would choose cloud-based setup, assuming there is no other teams needing same setup.  A team of six people is relatively small, so there is probably no need for highly detailed custom configurations. Also, if application will be relesed soon, there can be urge to have more ready approach with cloud-based setup, so there is no need to have setup self-hosted approach which can take some time and even some studying it before applying it
