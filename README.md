# my-ci-work-flow
•	Create Repository:
o	This establishes a new project repository on GitHub to store your code and configurations.
•	Set up CI Workflow:
o	GitHub Actions: An automation tool that runs workflows (scripts) in response to events like code pushes and pull requests.
o	ci.yml: A YAML configuration file defining the CI workflow.
•	Workflow Configuration:
o	Triggers (on): Specifies events that start the workflow (e.g., push and pull_request to main).
o	Jobs (jobs): Defines tasks to run as part of the workflow.
o	Steps (steps): Individual commands and actions to execute:
	Checkout: Uses actions/checkout@v2 to pull the latest code from the repository.
	Set up Node.js: Uses actions/setup-node@v2 to install the specified Node.js version.
	Run Script: Executes a simple shell command to print a message.

