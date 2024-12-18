**Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by Google.**

- **Linting**: *You can use tools such as Flake8 or Pylint. Both analyse the code to verify that it complies with best practices and style standards (PEP8 in the case of Python).*
- **Testing**: *Pytest is widely used for unit and integration testing. It can also be complemented with tox to test in multiple Python environments.*
- **Building**: *Although Python does not require a compilation process like other languages, tools such as setuptools or Poetry are used to package and manage dependencies.*

**What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask Google!**

- **GitLab CI/CD**: *Offers an integrated CI/CD workflow with repositories hosted by GitLab.*
- **CircleCI**: *A cloud-based CI/CD platform with easy integration for modern projects.*
- **Travis CI**: *Popular for open source projects hosted on GitHub.*
- **Azure DevOps**: *A complete CI/CD solution that can handle complex environments.*
- **Drone CI**: *A lightweight, self-hosted tool, ideal for container-based configurations.*

**Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?**

*For a small team like this (6 people), a cloud-based solution is typically the better choice. It minimizes the operational burden and allows the team to focus on delivering the application. However, if security and compliance are critical, a self-hosted setup might be necessary, provided the team has the resources to manage it effectively.*