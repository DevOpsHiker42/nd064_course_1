setup:
	# Create python virtualenv & source it
	python3 -m venv ~/.devops
	@echo "Created python virtualenv. You will need to activate it using:"
	@echo "source ~/.devops/bin/activate"

install:
	# This should be run from inside a virtualenv
	pip install --no-cache-dir --upgrade pip &&\
		pip install --no-cache-dir -r requirements.txt

