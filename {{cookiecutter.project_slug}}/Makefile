cookie:
	mv * .pre-commit-config.yaml .gitignore ../
	cd ..; make develop

develop:
	pip install -e '.[dev]'
	pre-commit install

setup-tests:
	pip install -e '.[test]'
