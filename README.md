* [The Rules](the_rules.md)
* [JUnit tests](unit_tests.md)
* [How did you get into programming?](https://www.youtube.com/watch?v=t32BNi3NEYA)
* [Art And Fear](art_and_fear.md)
* [Quick Command Line Tutorial - Windows](git/quick_command_line_tutorial_-_windows.md)
* [Quick Command Line Tutorial - Mac](git/quick_command_line_tutorial_-_mac.md)
* [Git Commands](git/git_commands.md)
* [GitHub Actions](github_actions.md)
* [Configure IntelliJ](intellij/configure_intellij.md)

* [Servlet](servlet/servlet.md)
* [Jetty](servlet/jetty.md)
* [Tomcat](servlet/tomcat.md)
* [Amazon Elastic Beanstalk](servlet/amazon/elasticbeanstalk.md)

### Create a new Java Project (with Gradle) in IntelliJ

Add `.gitignore`

```
.idea/
out/
.gradle/
build/
.DS_STORE
```

Open Terminal

```
git init
git add .
git commit -m "initial commit"
```

Create a repo on Github, copy the repo SSH url beginning with "git@github"

```
git remote add origin git@github...
git push origin main
```

Current Repo Status (most important command)

```
git status
```

Create a new branch

```
git checkout -b [name]
```

Change branches

```
git checkout [name]
```

Change branch to `main` and pull changes

```
git checkout main
git pull origin main
```