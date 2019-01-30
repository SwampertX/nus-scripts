# Instructions for check\_java

### Version 0.5 updates
- added summary messages
- pass the solution file as argument to facilitate <kbd>Tab</kbd> completion
- print out the diff message directly on top of saving to a diff file



This script is used to check answers for take-home labs by CS2040. This bash file supports the structure as below:

```
problem_folder
		input
				problem1.in
				problem2.in
				problem3.in
				.....
		output
				problem1.out
				problem2.out
				problem3.out
				.....
		problem.java (solution file)
```
## installation instructions (incomplete)
```
(it is a sketch)
curl -sL https://github.com/SwampertX/nus-scripts/raw/master/codecrunch/check_java
chmod +x check_java
sudo cp check_java /usr/local/bin/
```

## Usage
```
cd /path/to/problem_folder
check problem.java
```

### Credits
Prof Henry Chia for the original bash script that is not ready to be run globally.
