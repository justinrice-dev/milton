# Milton

An open-source Devops tool for the guy on the team that knows it all. 


![Drag Racing](./docs/images/milton.jpeg)

As an engineering organization grows, so does the need for internal tooling, version management, terminal configurations, and standardization. With the standardization, there is a need for a single internal tool to help with this configuration. Onboarding engineers in an all-remote engineering organization can be complex.

Milton is an open-source DevOps engineer to help a DevOps team support Developers with onboarding and local environment setup.

More importantly, Milton also tracks errors to reach out to Developers through Slack when mistakes occur. Developers get answers through Slack to their environment questions for ease of troubleshooting.

Milton allows DevOps teams to enforce and upgrade tooling behind the scenes.

## What's the Vision

Milton is a self-hosted solution with a UI, API, DB for tracking and storing configuration and the CLI that all developers downloaded within the organization. 

### Phase 1 - CLI to YAML
A Python CLI that reads from a YAML file for configuration. Within this configuration, users can configure.
Common languages and packages to be installed.
Configuration for internal tooling.
Services the Developers need access to.
### Phase 2 - CLI to API
CLI configuration is read from a DB
CLI configuration is stored and updated on a DB.
### Phase 3 - Reporting
Allow the user to see the number of errors and their type. 
Allow the user to configure the tool to report back to the user on Slack.




