
## Understanding Check Pt. 1
1) Where would you fit your automated tests in your Recipe project development pipeline?

Within a Github action that runs whenever code is pushed. This makes it so whenever you push code you can make sure it complies with the tests that ensure the functions and components work properly as well as following any lint or formatting guidelines. This also can ensure consistent code before merging pull requests.

2) Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, end to end tests are to make sure interaction with components from a user perspective is correct.




