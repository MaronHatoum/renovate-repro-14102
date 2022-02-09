## Minimal reproduction repository for renovatebot/renovate bug #14102
This is a minimal reproduction repository to help debug https://github.com/renovatebot/renovate/issues/14102

The current contents are docker-compose file and default renovate.json

Currently renovatebot will ignore any docker images with build context defined.

The build context here is public github repo.

The referenced labels/tags in the repo are not the latest and they follow the semver.
