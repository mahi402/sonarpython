
go to project directory, you can more tests to project, if u need more coverage

pip install -r requirements.txt


py.test --cov-report xml:coverage.xml --cov=. --junitxml=result.xml  test.py

above command generates coverage.xml and result.xml
after setting up sonrqube with project name as sonar-flask
go to python-flask folder and run this

sonar-scanner -Dsonar.projectKey=sonarqube-flask -Dsonar.sources=./ -Dsonar.host.url=http://localhost:9000 -Dsonar.login=5a2ba4d06d9aa73f791945fa88efb075f3636cdb
