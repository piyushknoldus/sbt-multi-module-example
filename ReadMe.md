###sbt-multi-module-example

A sample example to provide a multi-project build using sbt

####it contains - 
- A single build.sbt file which allows for centralized configuration, dependency and build management
- Each sub-project contains only its source code
- Sub-projects can depend on other sub-projects
- Only deliverable sub-projects produce a fat-jar using sbt-assembly

####Example structure
`
sbt-multi-module-example/

    common/
        src/
        test/
    users/
        src/
        test/
    project/
        build.properties
        plugins.sbt
    build.sbt
    .gitignore
    .scalafmt.conf
    ReadMe.md
`
