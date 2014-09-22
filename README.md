# ansible-sprint

## Build Instructions
	
	pip install ansible
	git clone --recursive http://github.com/brainstorm/ansible-training-content
	ansible-playbook build.yml -i localhost, && open output/scilifelab/index.html

### Dependencies

* PyYAML

## Syntax Checking

```
python syntax_check.py *.yml
```
