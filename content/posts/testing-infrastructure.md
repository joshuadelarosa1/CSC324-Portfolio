+++
date = '2026-04-15T13:47:19-05:00'
draft = false
title = 'Testing Infrastructure'
+++

## Testing Infrastructure

![testing_infrastructure_snippet](/CSC324-Portfolio/images/testing_infrastructure_snippet.png)

![testing_infrastructure_snippet 2](/CSC324-Portfolio/images/testing_infrastructure_snippet2.png)

Yes, my tests are automated so they only take "1-click" and run with the build validation. We run our tests by using a terminal line and directly running the tests with lua. If any tests fail, our testing suite lets us know and the other tests continue to run. While my tests did not catch unexpected behavior in the mechanics themselves of the game, running my tests showed an initialization issue caused by love.window not functioning properly during the module load time. This was harmful for the other files which depended on our scene manager, and prompted me to add "guarding" on getting the desktop dimensions in the cases where love.window is taking longer to load. This would prevent the lua 'blue screen' that happens when an error occurs.  

This snippet is located in the GrinnSim repository under the tests/run_all_tests.lua file, associated with pull request 84. Connor wrote this automation for running our tests, and as a group we added more tests we thought would be useful. Tests that I added include: test_character_creation, test_circle_nav, and test_stats_academics. I used ChatGPT to help write the tests themselves, but came up with ideas on what to test on my own. I udpated the code produced from ChatGPT as needed.

This demonstrates that I have completed this competency because (1) my tests run automatically along with the other tests in the suite and (2) we had an occurance where this test demonstrated a weakness (although not realted to game mechanics) in our manager.lua file.