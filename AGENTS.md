# Instructions

The goal of this project is to group various open source projects I have into relevant groups so I can find them quickly.

## How to access the repos

Use the github cli (gh) to pull the repos. My machine has access to my github account.

- DO NOT MAKE ANY CHANGES TO ANY REPOS
- ONLY USE THE CLI TO GET REPO INFORMATION

## Grouping Instructions

- All the changes go into README.md
- These are the high level groups:
  - templates
  - packages (npm, docker, etc)
  - showcase (these are examples, demos, etc)
  - config (dotconfig, any sort of config, etc)
  - apps (anything that is currently deployed, I think there's only one now which is my website dineshpandiyan.com)
- Infer the project's purpose by reading the repo name and description
- While writing the list in README.md append the text "(archived)" to the repo name if the repo is archived
- Use the github cli to fetch the repos
- sort them in this priority:
  - top priority: most recent commit activity activity if the activity was in the last year. or stars reverse order of activity was more than a year ago. if stars are equal, prefer activity reverse order.
  - second priority: stars reverse order. if stars are equal, prefer activity reverse order.
  - third priority: title ascending order
- Ignore all private repos
- Ignore all repos that I did not create (i.e the repos I forked)
