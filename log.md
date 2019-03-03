# 100 Days Of Code - Log

### Day 0: March 1, 2019
##### First GitHub repository

**Today's Progress:** I'm working on Python script to migrate some of videos from our company's CDN provider to youtube. The part of the script that is currently written uses calls to API that CDN provider has, downloads each file and saves it's infornation (id, name and filepath) to JSON.

**Up next:**  
- [ ] Refactoring script to separate utility functions from main call.
- [ ] Modify script so it would take credential as commandline arguments.
              
**Thoughts:** This is my first serious project in Python and I think it will help me to grow professionaly towards geting a job in programming. I'm going to learn google's youtube API and SQLAlchemy and this should be superhelpful for backend development.

**Link to work:** [GitHub repository](https://github.com/Orithil/ep-migrate)

### Day 2: March 2, 2019
##### Get comfortable with argparse

**Today's Progress:** Learned about argparse and separated server credential completely from code. Now it can be provided from separate JSON file. Also learned about sys.exit() function wich allows to exit script after catching exception or error. Also learning how to do atomic commits in git mixing this approuch with gitflow. 

**Up next:**  
- [ ] Refactoring script to separate utility functions from main call.
- [x] Modify script so it would take credential as commandline arguments.
- [ ] Add google-api authentication

**Thoughts:** Maybe I'm running in front of the train as it seems pretty complex, but I know a little bit about [git flow approach](https://nvie.com/posts/a-successful-git-branching-model/) (not the git-flow wrapper itself) and it seems very convenient. But I've never used atomic commits and it seems reasonable to master. [This article](https://seesparkbox.com/foundry/atomic_commits_with_git) from Spakbox explains topic in comprehensible manner.

**Link to work:** [GitHub repository](https://github.com/Orithil/ep-migrate)

### Day 3: March 3, 2019
##### Refactoring is tedious but rewarding

**Today's Progress:** Today I was refactoring and adding docstrings to script to make it more readable. I think now it loks more like a proper python module. It was a bit tedious to do as I had to re-read all the code to properly resolve import dependecies. And of course I broke thing or two in the process so I had to re-test it but now __main__ looks much lighter and I hope it is easier to read.

**Up next:**  

- [x] Refactoring script to separate utility functions from main call.
- [x] Modify script so it would take credential as commandline arguments.
- [ ] Add google-api authentication

**Thoughts:** Well, I failed to make atomic commits in refactoring process. It is still a thing to learn. However git flow approach still works for me. 

**Link to work:** [GitHub repository](https://github.com/Orithil/ep-migrate)
