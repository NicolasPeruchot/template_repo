cookie:
	mv * .pre-commit-config.yaml .gitignore ../
	cd ..; make develop; rm -rf {{cookiecutter.project}}.egg-info; mkdir -p .github/workflows; mv ci.yaml .github/workflows

develop:
	pip install -e '.[dev]'
	pre-commit install

setup-tests:
	pip install -e '.[test]'
