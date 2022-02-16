Simple introduction：
	1. This project is based on python 3.9 and java 11.
	2. Using pytest to test the API.
	3. Using pycharm to set up and execute the project.

How to run:
	You should run the test method under TestHttpPost.py, TestHttpPost.py, TestHttpDelete.py. Double click the test method, such as test_http_post, then right click, run by pytest.


Two issues I found:
	1. Delete API can be executed by READ access, but in the document, it says delete API needs WRITE access.
	2. Delete API is not working well, although it can be executed and gets 200 response, but in the database, the data is still existing.