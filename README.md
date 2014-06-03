Gradle GUG presentation
===============

Materials to gradle GUG presentations - part II - multi modules example.
All modules can be run separately, gradlew is provided.
Presentation can be found at https://docs.google.com/presentation/d/1hZinPqC4yKHmLeokKeUxqX54k5zHx0PALFFgjkeDgW4/edit?usp=sharing

Modules
-------
* gradle-presentation-multi-payments -- parent, multi-module configuration, configuration for all projects, libraries in separate file
* gateway-schema -- custom dependency configuration, JavaExec type task, source generation hooked to lifecycle
* payments-api -- no separate build.gradle file project.
* payments-impl -- dependencies for the build script.
* payments-utils -- only additional dependency configuration


