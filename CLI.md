
```
rm -rf 00-free-code-challenges
rm -rf 01-responsive-web-design
rm -rf 02-javascript-algorithms-and-data-structures
rm -rf 03-front-end-development-libraries
rm -rf 04-data-visualization
rm -rf 05-back-end-development-and-apis
rm -rf 06-quality-assurance.git
rm -rf 07-scientific-computing-with-python
rm -rf 08-data-analysis-with-python
rm -rf 09-information-security
rm -rf 10-coding-interview-prep
rm -rf 11-machine-learning-with-python
rm -rf 13-relational-databases
rm -rf CtCI-6th-E-JS
rm -rf CtCI-6th-E-JS-ES2015
rm -rf CtCI-6th-E-Python
rm -rf CtCI-6th-E-cpp
rm .gitmodules
rm -rf .git
git init
git branch -M main
git remote add origin https://github.com/freeCodeChallenges/interview-arcade.git
git submodule add https://github.com/freeCodeChallenges/00-free-code-challenges.git
git submodule add https://github.com/freeCodeChallenges/01-responsive-web-design.git
git submodule add https://github.com/freeCodeChallenges/02-javascript-algorithms-and-data-structures.git
git submodule add https://github.com/freeCodeChallenges/03-front-end-development-libraries.git
git submodule add https://github.com/freeCodeChallenges/04-data-visualization.git
git submodule add https://github.com/freeCodeChallenges/05-back-end-development-and-apis.git
git submodule add https://github.com/freeCodeChallenges/06-quality-assurance.git
git submodule add https://github.com/freeCodeChallenges/07-scientific-computing-with-python.git
git submodule add https://github.com/freeCodeChallenges/08-data-analysis-with-python.git
git submodule add https://github.com/freeCodeChallenges/09-information-security.git
git submodule add https://github.com/freeCodeChallenges/10-coding-interview-prep.git
git submodule add https://github.com/freeCodeChallenges/11-machine-learning-with-python.git
git submodule add https://github.com/freeCodeChallenges/13-relational-databases.git
git submodule add https://github.com/CareerHunter/CtCI-6th-E-JS.git
git submodule add https://github.com/CareerHunter/CtCI-6th-E-JS-ES2015.git
git submodule add https://github.com/CareerHunter/CtCI-6th-E-Python.git
git submodule add https://github.com/CareerHunter/CtCI-6th-E-cpp.git
git add .
git commit -m 'first commit'
git push --set-upstream origin main --force
```