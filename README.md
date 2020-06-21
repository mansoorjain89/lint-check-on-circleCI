# learn-ci
Mini project to learn CI

# Introduction:

CircleCI is a tool that defines an automated testing environment; getting a CircleCI badge that reads "Passed" on a repository indicates that the project code has passed all lint tests. 

CircleCI uses a YAML file to identify how you want your testing environment set up and what tests you want to run. On CircleCI 2.0, this file must be called config.yml and must be in a hidden folder called .circleci. On Mac files and folders whose names start with a period are treated as system files that are hidden from users by default.

# File Summary:
1. `.circleci/config.yaml`: Configuration file for CircleCI integration
2. `Makefile`: Make file to create shortcuts to run commands
3. `hello.py`: File where the app code is written
4. `requirements.txt`: Dependent pkgs to be installed on docker containers

# Sample Output

- circleCI - `pass` If there are no syntatical errors on the files that are pushed.
- circleCI - `fail` If any syntatical errors found in the code
