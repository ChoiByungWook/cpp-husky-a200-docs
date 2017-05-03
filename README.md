# GETTING STARTED
!!!FAMILIARIZE YOURSELF WITH THESE TOPICS!!!

[Husky Wiki](http://wiki.ros.org/Robots/Husky) - Our platform

- [Husky-A200-Manual](https://github.com/rhrt/Devices/blob/master/Motors/Clearpath%20Husky%20A200/Husky-A200-UGV-UserManual-0.12.pdf)

[ROS](http://wiki.ros.org/ROS/Introduction) - Robot Operating System. Libraries and tools that will be used to build our applications.

[ROS](http://wiki.ros.org/ROS/Tutorials) - Robot Operating System. Libraries and tools that will be used to build our applications.

[Catkin](http://wiki.ros.org/catkin/Tutorials) - Build system for ROS.

# SETTING UP

1. [14.04 Linux](http://releases.ubuntu.com/14.04/) - Either dual boot or run on a vm.
 - [Dual Boot](https://www.howtogeek.com/214571/how-to-dual-boot-linux-on-your-pc/)
 - [Virtual Box](https://www.virtualbox.org/)
2. [ROS](http://wiki.ros.org/indigo/Installation/Ubuntu) Install on your linux os.
3. [Git](https://git-scm.com) - Your favorite version control. THIS IS HOW WE ORGANIZE OUR CODE.
4. [Github](https://github.com/cpp-self-driving-husky) - Where our code is stored.
5. [Slack](https://cpp-self-driving.slack.com) - How we communicate.
6. [Task board](https://kanbanflow.com/board/d7b30b8e86d513caf774822dc96e9d70) What are you doing? What am I doing? Request to be added.
7. Request to be added to the emailing list.

# CODING/DESIGN STANDARDS

[C++ Coding Standards](https://google.github.io/styleguide/cppguide.html)

[Python Coding Standards](https://google.github.io/styleguide/pyguide.html)

[IMPORTANT!!! How to commit a change using git.](https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html)
- [Commit early and often! Keep them small!](http://sethrobertson.github.io/GitBestPractices/#commit)
- [Writing good commit messages!](http://chris.beams.io/posts/git-commit/)
- RECOMMENDED PRACTICE
 1. Checkout the project. - git clone projecturl
 2. Checkout into a local branch for each feature change. - git checkout -b featurename
 3. Work in this branch
- CHECKLIST BEFORE YOU COMMIT YOUR CHANGES
 1. Do an update: git pull && git merge <--- Ensure your changes are compatible with the latest code.
 2. Rerun your tests. (Unit tests, Integration tests)
 3. Run in simulation successfully.
 4. Push your changes from your local branch. - git push
 5. Submit a pull request.
 6. Address all feedback provided in the pull request.
 7. Repeat steps 2-7 until all issues are resolved in the pull request.

[Pull request Tutorials](https://yangsu.github.io/pull-request-tutorial/) - This is how we do code reviews.

[Good example of a software design document](https://github.com/cpp-css/cpp-parking-design-doc)

# SOFTWARE DEVELOPMENT/TESTING

[Simulation](http://wiki.ros.org/husky_gazebo)

[Why unit testing is important](https://www.quora.com/What-is-software-unit-testing-and-why-is-it-important)

[Integration Tests](https://en.wikipedia.org/wiki/Integration_testing)