# Intro to Rails

The purpose of this project is to introduce you to Rails's different moving parts. This will happen through a series of steps in the form of branches. Each step will build on the previous one.

## installation
- clone the project:

	```bash
	git clone https://github.com/Devbootcamp/challenge-intro-to-rails.git
	```
- install gems:

	```bash
	bundle install
	```
- create database.yml file

	```bash
	touch config/database.yml
	```
- configure database.yml file by following/reading the database.example.yml file.
- create the databases:

	```bash
	rake db:create
	```
- run the server:

	```bash
	rails s
	```
- visit localhost:3000 to see Welcome to Rails page.


When you're done, check out the step 1 branch. You will be doing this throughout this challenge. Always start at README.md and when you're done with all the instructions, move to the next branch. Here is a list of the branches:

- step_1_file_structure
- step_2_static_flow
- step_3_dynamic_flow
- step_4_crud
- step_5_associations_and_crud
- step_5.1_associations_and_crud
- step_5.2_netsted_resources
- step_6_testing
- step_6.1_unit_testing
- step_6.2_controller_testing
- step_6.3_feature_testing
- step_7_styling
- step_8_javascript
