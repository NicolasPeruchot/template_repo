cookie:
	mv * .pre-commit-config.yaml .gitignore .github/* ../
	cd ..; make develop; rm -rf {{cookiecutter.project}}.egg-info

develop:
	pip install -e '.[dev]'
	pre-commit install

setup-tests:
	pip install -e '.[test]'
