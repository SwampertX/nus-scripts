# Instructions for check\_java

### Version 0.5 updates
- added summary messages
- pass the solution file as argument to facilitate <kbd>Tab</kbd> completion
- print out the diff message directly on top of saving to a diff file
## Installation instructions
```
curl -sL https://github.com/SwampertX/nus-scripts/raw/master/codecrunch/check_java > check_java
chmod +x check_java
sudo mv check_java /usr/local/bin/

```
## Directory structure
This script is used to check answers for take-home labs by CS2040. This bash file supports the structure as below:

```
problem_folder
		(you are here)
		input
				problem1.in
				problem2.in
				.....
		output
				problem1.out
				problem2.out
				.....
		problem.java (solution file)
```

## Usage
```
cd /path/to/problem_folder
check_java problem.java

```

### Credits
Prof Henry Chia for the original bash script that is not ready to be run globally.
