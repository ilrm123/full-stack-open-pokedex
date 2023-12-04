In this hypothetical situation, the application is coded with Python. The application is quite small, because the team developing it consists of only 6 people.

With Python applications, a very common and popular tool for linting the code is Pylint, so this application shall use Pylint. For testing, the application utilizes another very popular tool, Pytest. Finally, for building, there is no separate tool because Python applications do not require a separate build step.

In addition to Jenkins and GitHub Actions, there are many different CI setups as both self-hosted and cloud-based environments. The self-hosted options include Travis CI, GitLab CI/CD, Bamboo and TeamCity. The cloud-based options include Bitbucket Cloud, AWS CodePipeline, BitRise, CloudBees and Codefresh. There are also providers that offer both self-hosted and cloud-hosted CI setups, such as CircleCI.

Because the aforementioned hypothetical application is small and worked on by a small team, the better option for a CI setup is a cloud-based environment such as GitHub Actions. This is a simpler solution in terms of development and setting up the project, and should provide enough resources for a small application. A self-hosted environment could become too complicated for the developers and maybe even be overkill in terms of what is needed. 
