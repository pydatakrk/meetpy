
.PHONY: test

test:
	pytest

test-last-failed:
	pytest --last-failed

test_: test-last-failed

server:
	./manage.py runserver 0.0.0.0:7832
