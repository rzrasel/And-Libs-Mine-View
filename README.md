# And-Libs-Mine-View
And Libs Mine View

### GIT Command
```git_command
git init
git remote add origin https://github.com/rzrasel/And-Libs-Mine-View.git
git remote -v
git fetch && git checkout master
git add .
git commit -m "Add Readme & Git Commit File"
git pull
git push --all
```

Download
--------

Maven Repositories
```maven
allprojects {
    repositories {
        maven { url 'https://dl.bintray.com/rzrasel/android-mine-view/' }
    }
}
```

Download the latest JAR or grab via Maven:
```xml
<dependency>
	<groupId>com.adept.power-pack</groupId>
	<artifactId>and-mine-view</artifactId>
	<version>100.00.01</version>
	<type>pom</type>
</dependency>
```
or Gradle:
```groovy
implementation 'com.adept.power-pack:and-mine-view:100.00.01'
```