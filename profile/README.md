# Law&Orga

Welcome to our GitHub space. All of Law&Orga's code is here. This document collects important information for the developers on this project. It contains rules that should be followed and material that is recommended for developing.

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

### All Other Names

The thing to be named will be called `object`. Any `object` that needs a name, for example a database or a docker image, should have the same as the repository that is the reason for this object's existence.  

If some signs are not allowed or only a specific amount of letters is allowed the name should be changed in the following order until the name is allowed:

1. Remove `-` signs
2. Remove `lawandorga`
3. Remove signs starting from the back

If the `object` only applies to a specific branch the branch should be added at the end. The branch should not be removed, steps 1 to 3 need to be done before the branch is added.

## Material

The following material is recommended to be understood, because the development tries to follow the principals discussed in those books or articles.

[https://basecamp.com/shapeup](https://basecamp.com/shapeup)


