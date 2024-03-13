# Lab Report 4 - Vim (Week 7)

## Task Execution

### Step 1: Clone Repository

**Screenshot:** ![Clone Repository](lr71.jpg)
![Clone Repository](new.jpg)
![Clone Repository](new1.jpg)
![Clone Repository](new3.jpg)

**Keys Pressed:** 
- `git clone git@github.com:syna230404/lab7.git``<enter>`

**Summary of Command:** Cloned the repository from my GitHub account using the SSH URL.

### Step 2: Run Tests (Demonstrating Failure)

**Screenshot:** ![Run Tests - Failure](lr7.jpg)

**Keys Pressed:** 
- `javac ListExamples.java <enter> javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java <enter> java -cp ../libs/junit-4.13.2.jar:../libs/hamcrest-2.2.jar:. org.junit.runner.JUnitCore ListExamplesTests <enter>`

**Summary of Command:** Executed the test script to demonstrate initial test failures.

### Step 3: Edit Code to Fix Failing Test

**Screenshot:** ![Edit Code](lr72.jpg)

**Keys Pressed:** 
- `vim ListExamples.java` `<enter>`
- `44j e x i2 <esc> :wq!` `<enter>`

**Summary of Command:** Opened the file in Vim to edit and fix the failing test.

### Step 4: Run Tests Again (Demonstrating Success)

**Screenshot:** ![Run Tests - Success](lr73.jpg)

**Keys Pressed:** 
- `bash test.sh <enter>`

**Summary of Command:** Re-executed the test script to demonstrate successful test runs after code fix.

### Step 5: Commit and Push Changes

**Screenshot:** ![Commit and Push](push.jpg)

**Keys Pressed:** 
- `git add .``<enter>`
- `git commit``<enter>`
- `git push` `<enter>`

**Summary of Commands:** Staged changes, committed with a descriptive message, and pushed to GitHub.

## Conclusion

In this lab report, I successfully completed the tasks outlined for Week 7. Each step was documented with screenshots and descriptions of the keys pressed. The code was edited to fix failing tests, and changes were committed and pushed to GitHub. This exercise provided hands-on experience with using Vim, Git, and command line tools for software development tasks.
