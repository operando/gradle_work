# Gradle Work

## Setup Gradle

curl -s get.gvmtool.net | bash

source "/Users/xxx/.gvm/bin/gvm-init.sh"

gvm install gradle


## Command

gradle tasks

gradle properties

gradle clean

gradle init --type java-library

gradle --gui

gradle --daemon [task name]

gradle --stop

gradle wrapper


## Options

gradle -i(--info)

gradle -s(--stacktrace)

gradle -S(--full-stacktrace)

gradle -d(--debug)

gradle -q(--quiet)

gradle -b(--build-file) [gradle file]

gradle -?(-h or --help)


## GRADLE_OPTS

-Dorg.gradle.daemon=true


## jar 

```
// output jar ${baseName}-${appendix}-${version}-${classifier}.jar
jar {
    baseName = 'example'
    appendix = 'bin'
    version = '0.1'
    classifier = 'jdk17'
}
```
