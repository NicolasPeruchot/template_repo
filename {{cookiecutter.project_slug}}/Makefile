cookie:
	mv * .pre-commit-config.yaml .gitignore ../
	cd ..; make install

install:
	python -m pip install -r requirements.txt
	pre-commit install
