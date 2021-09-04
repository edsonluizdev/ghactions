# Nootes

## Create a workflow
- Workflows define the event that triggers actions.
- Workflows define with actions to run.
- Repositories can contain multiple workflows.
- Workflows are stored in `.github/workflows`
- Is good practice to give workflow name that describe what the workflow does.
- Define the github event that will trigger the workflow using the `on` key word.

## Events
Most common events are:
- push
- pull_request
- release

You can use one or multiple events using brackets.
```
on: push
on: [push, pull_request]
```