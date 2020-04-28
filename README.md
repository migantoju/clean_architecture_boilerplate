<p align="center">
	<img src ="https://cdn.urbvan.com/website1.0/menu/logo.svg" alt="Urbvan Transit"
	width="400" height="150"
	/>
</p>

# Urbvan Clean Architecture (AKA Hexagonal Architecture) Boilerplate

# Overview ℹ️
This a template to start a new project with all the configuration used
and plugin used by Urbvan Backend Team.

This boilerplate has configuration to keep the better code style for all,
with `.editoconfig` and `pre-commit`.

- Python 3.7
- Pyenv
- Sentry
- Pre-commit
- Poetry
- editorconfig

# Configuration 🛠️
Firs of all you need to clone this repository and change the main folder name
`clena_architecture_boilerplate` -> `your_awesome_project`.

Then, you need to install all the dependencies, this project is managed by
`poetry`, and the other part, for development purpose is with pip.

To install the project dependencies, you need to:
```shell script
$ poetry install
```


And the development packages with pip:
```shell script
$ pip install -r conf/requirements.txt
```

This is to keep the development dependencies away from production and necesary
package for the right operation of the project.

So, if you need to install development dependencies is with `pip` and for project
with `poetry`.

Now it's time to install pre-commit, this is too easy, only need to write in terminal:
```shell script
$ pre-commit install
```
And that's all. You're ready for the next big and great project of Urbvan ❤️.🥳

Good luck and be awesome! 🎉

Created with ❤️ by Urbvan.
