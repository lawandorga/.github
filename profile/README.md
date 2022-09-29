# Law&Orga

Welcome to our GitHub space. All of Law&Orga's code is here.

## Rules

Here are some rules, that can not be enforced by code. These rules always apply unless stated otherwise within the rule.

### Repository Names

1. Every repository should start with `lawandorga` in order to make the github search easier.
2. In the middle should be a meaningful name that describes the content of the repository, preferrably one word.
3. In the end should be the type of the repository, this can be one of the following: `server`, `service`, `frontend` or `utils`. If the type is `server` the repository should be able to create a whole server, if the name is `service` it should be a deployable app for example a docker container, if it is `frontend` it should be deployable on a cdn and `utils` should be installable in other repositories.
4. If the repository is out of date ist should adhere to the other rules and add `obsolete` in the end.

Those rules result in the following pattern:

lawandorga-[name]-[type]?(-obsolete)

Examples of repository names:

lawandorga-django-utils \
lawandorga-chat-frontend

### Image Names

Image names should be the same as repository names. If the image is not for the main branch it should include the branch at the end.

### Database Names

Database names should be the same as repository names, but without the type. If the database is not for the main branch it should include the branch at the end.

### Instance Names And Container Or Web App Names

These names should be the same as the repository name. If some signs are not allowed or only a small amount of chars the names should be changed in the following order until the name is allowed:

1. Remove `-` signs
2. Remove `lawandorga`
3. Remove signs starting from the back

If the instance only applies to a specific branch the branch should be added at the end.
