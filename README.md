# GitHubStatsGraphQL

An Android application for showing stats of an GitHub organization using the new [GraphQL API](https://developer.github.com/early-access/graphql/) and the [Kotlin](https://kotlinlang.org/) programming langauge.

## Installation

Download the [latest release](https://github.com/KSWE-2016-17/GitHubStatsGraphQL/releases/latest) and install it on your device or emulator.

## Building yourself

The following tools are needed:

- [JDK](http://www.oracle.com/technetwork/java/javase/downloads/index-jsp-138363.html)
- [Android SDK](https://developer.android.com/studio/index.html)

Next, download the sources or clone them.<br>
The GitHub API requires you to supply authorization (your username and password), which is done by creating a `secrets.properties` file in the root of the project.

The contents should look like this:

```
GITHUB_USERNAME=your_username
GITHUB_PASSWORD=your_password
```

You can now import the project into `Android Studio` or build the project on the command line and install it.<br>
To build:

```shell
./gradlew assembleRelease
```

To run:

```shell
./gradlew installRelease
```
