Zerocode Hello World
===

#### How to run the examples?
Ans: The same stuff you do everyday for any maven project.

```

Step-1: 
Import the maven project "zerocode-rest-help" using Eclipse or IntelliJ or your favourite IDE
          * i.e. /zerocode-hello-world/pom.xml, 
          * mvn clean install -DskipTests
          * The above command brings all the libs to the local .m2 repo

Step-2: 
          * Run the JustHelloWorldTest.java test (it uses GitHub REST https apis)
          * i.e. src/test/java/org/jsmart/zerocode/testhelp/tests/helloworld/JustHelloWorldTest.java
          * Then fiddle with the assertions section and run the test again, observe the PASS/FAILURES at the console.
          
          * To run more tests go to individual package and run. e.g. folders-  helloworldgithub, helloworldmore etc

-done- 
That's it. It is as simple as that.

(So when your tests grows to thousands in numbers, you organize them by feature, by consumer, by profile etc. Hence Zerocode helps)

Step-3: (Optional Step)
Start the Local Mock REST server
          * i.e. just Run as main() -> test/.../RunMeFirstRESTServer.java. 
          * Then you can run the src/test/java/org/jsmart/zerocode/testhelp/tests/helloworldmore/JustHelloWorldMoreTest.java

```

> -OR-

```
Run as Suite:
          * src/test/java/org/jsmart/zerocode/testhelp/tests/HelloWorldGitHubSuite.java

More examples:
          * src/test/java/org/jsmart/zerocode/testhelp/tests/helloworldmore/JustHelloWorldMoreTest.java
          * -or- Browse under test/resources/ folders- helloworld, helloworld_github_REST_api, helloworld_more
```
-done-

Eclipse:
=====
Open a matching java file -> Ctrl + Shift + R
Open a matching JSON file -> Ctrl + Shift + R
To navigate to file -> Ctrl + Click

IntelliJ:
=====
Open a matching java file -> Ctrl + n
Open a matching JSON or XML file -> Ctrl + Shift + n
To navigate to file -> Ctrl + Click

Now see the
* Results @ `target/zerocode-test-reports`
* Logs @ `target/logs/zerocode_test_logs.log`
* Test coverage CSV Report @ `target/zerocode_full_report_YYYY-MM-DDTHH-MM-SS.SSS.csv`
* Test coverage Chart @ `target/zerocode_results_chart_YYYY-MM-DDTHH-MM-SS.SSS.html`

