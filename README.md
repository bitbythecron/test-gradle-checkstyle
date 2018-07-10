# test-gradle-checkstyle
Just clone and run:

    ./gradlew clean build

And watch it fail spectacularly:

```
FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':checkstyleMain'.
> Unable to create a Checker: configLocation {/Users/myuser/workspace/test-gradle-checkstyle/buildConfig/checkstyle/checkstyle.xml}, classpath {/Users/myuser/workspace/test-gradle-checkstyle/build/classes/java/main:/Users/myuser/workspace/test-gradle-checkstyle/build/resources/main}.

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 1s
4 actionable tasks: 4 executed
$ pwd
/Users/myuser/workspace/test-gradle-checkstyle
$ git init
Initialized empty Git repository in /Users/myuser/workspace/test-gradle-checkstyle/.git/
```
