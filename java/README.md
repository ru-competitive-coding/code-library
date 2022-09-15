# Java Code Library
The code in this repository is written in *Java 11* for compatibility with Kattis (https://open.kattis.com/help/java).

## Project Setup (IntelliJ)
The following describes how to set up the project in IntelliJ.

1. Clone the repository. Steps will vary depending on how you authenticate with GitHub (HTTPS vs SSH).
    - https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
    - https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github
2. Load up IntelliJ
3. Open a new project
    - `File > Open` if you have a project already open
    - `Open` if IntelliJ displays the project picker
4. Navigate to where the repository is cloned, then select the `java` folder within.
    - Suppose you cloned the repo to `C:\dev\code-library`. You should open `C:\dev\code-library\java` using IntelliJ
5. IntelliJ should automatically detect the Gradle project. Wait for everything to load, it may take 30+ seconds for the
   first load.

Next, we'll verify our setup by running the tests using `Gradle`.
1. Open the Gradle tool window in IntelliJ. It will probably be docked on the right-hand side of IntelliJ
   - If it's not visible, you can open it manually using `View > Tool windows > Gradle`
2. Run the task: `ru > lib > verification > test`
3. You should see the tests running, and passing, in the "Run" window at the bottom of the screen.
