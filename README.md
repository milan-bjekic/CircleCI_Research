# CircleCI_Research
For research purpose (Youtube video: CircleCI Tutorial w/ Demo Project in 22 Mins)
https://www.youtube.com/watch?v=4dp4JFpOpX0

# Cloned the repo
```
cd C:\Users\milanb\dev\new_03\circle_ci_01
git clone https://github.com/milan-bjekic/CircleCI_Research.git
```

# Run the code locally
```
cd C:\Users\milanb\dev\new_03\circle_ci_01\CircleCI_Research
python main.py
```

# Run the test code locally
```
cd C:\Users\milanb\dev\new_03\circle_ci_01\CircleCI_Research
python .\main_test.py
```

# Commit and push the code changes you made
```
cd C:\Users\milanb\dev\new_03\circle_ci_01\CircleCI_Research
git add .
git commit -m "Initial commit"
git push -u origin main
```
We did not have to add remote origin because we cloned the repo,
if we did not, we would need to add it:
```
git remote add origin https://github.com/milan-bjekic/CircleCI_Research.git
```
You will be asked to login for the push.

# Setting up circleci yaml file
```
cd C:\Users\milanb\dev\new_03\circle_ci_01\CircleCI_Research
mkdir .circleci
touch .circleci/config.yml
```

# Commit and push the code changes you made
```
cd C:\Users\milanb\dev\new_03\circle_ci_01\CircleCI_Research
git add .
git commit -m "circleci configuration"
git push
```
You can now tun the workflow in CircleCI Dashboard and it should be success