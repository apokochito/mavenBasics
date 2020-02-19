# Maven Basics
- Libraries (**master branch**)
    - Lombok
    - Jackson
    - Orika
    - Log4J & Slf4J (Don't forget add slf4j dependency (compile Scope) to your classpath - "Project modules" for IntelliJ IDEA)
    - Test JUnit4 (Don't forget add JUnit4 to your classpath)
    - Jacoco Report (test goal to generate it)
- Maven Basics (**maven branch**)
    - Lifecycles
    - Phases (validate >> compile >> test (optional) >> package >> verify >> install >> deploy)
    - Plugins
    - Dependencies
    - Artifactory
    - Version
    - Profiles (Run perfiles with mvn package command, it is to activate a profile, add -P option, mvn package -Pxtest)
