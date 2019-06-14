# Bowling-Game-
Bowling Game 
----------------------------------------------------------------------------------------------------------------------------------------
Main : /src

Test : /test

----------------------------------------------------------------------------------------------------------------------------------------
Install and configure karma test-runner
------------------------------------------
npm install -g karma

npm install -g karma-mocha

npm install -g karma-chai

karma init

	Testing framework: mocha
	Require.js: no
	Capture browser: Chrome
	Source and test files: src/*.js test/*.js
	Excluded:
	Run tests on change: yes
  
Open the created configuration file and change frameworks: ['mocha'], to frameworks: ['mocha', 'chai'],

-------------------------------------------
Execute karma test-runner
-------------------------------------------
Kick-start the test runner typing karma start and hitting ENTER
