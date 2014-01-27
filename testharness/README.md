## Test Harness

A simple to tool to help you test and score your automatic activity coder.

## How to use it:

1. Install node and node package manager
2. Run 'npm install' in this folder to get all the dependencies.
3. Call codeharness and point it to your coding service and the test case you want to run:

	// node codeharness.js [url-of-autocoder] [path-to-test-csv]
	> node codeharness.js http://localhost:3000/classify.json "../data sets/aiddata22_WB500.txt"

4. Results will be printed to the screen. The score is cumalitive, so the last printed value is your final score.

Your service must accept 'description' as a GET parameter.
