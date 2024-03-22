# Copier project template

This is a template to kickstart your Python project. 🚀

Prerequisite: make sure you have [`copier`](https://copier.readthedocs.io/en/stable/) installed

To use this template, run:

```bash
copier copy --trust --vcs-ref <BRANCH/RELEASE> gh:ykerus/copier-project-template <YOUR-NEW-PROJECT>
```

For example:

```bash
copier copy --trust --vcs-ref main gh:ykerus/copier-project-template my-new-project
```

Or a specific version:

```bash
copier copy --trust --vcs-ref v0.0.1 gh:ykerus/copier-project-template my-new-project
```

For local testing:

```bash
copier copy --trust --vcs-ref HEAD path/to/copier-project-template my-new-project
```
