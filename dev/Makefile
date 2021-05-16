setup:
	python3 -m venv ~/.finance

install:
	pip install -r requirements.txt

test:
	python -m pytest -vv --cov=financelib tests/*.py

lint:
	pylint --disable=R,C financelib

all: install lint test
