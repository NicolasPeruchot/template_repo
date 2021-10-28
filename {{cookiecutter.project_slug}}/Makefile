cookie:
	mv * .pre-commit-config.yaml .gitignore ../
	cd ..
	rm -rf {{cookiecutter.project_slug}}/

install:
	python -m pip install -r requirements.txt
	pre-commit install
