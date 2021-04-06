## What's the Vision

Milton is a self-hosted solution with a UI, API, DB for tracking and storing configuration and the CLI that all developers downloaded within the organization. 

The concept is to build the CLI first, a simple tool for teams that want to grow, without the overhaul of having a service to manage.

The second phase is adding the ability for something to be hoseted in order to expand the sanity to something that isn't a YAML file.

We then work the DB and API into something that can be deployed and use the deployment for creating communication to the ussers

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
