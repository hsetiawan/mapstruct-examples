# MapStruct Examples

This repository contains examples showing how to use [MapStruct](http://mapstruct.org/), a Java annotation processor for the generation of type-safe bean mapping classes.

Currently, the following examples exist:

* _mapstruct-on-ant_: Shows how to use MapStruct in Ant-based projects; to build this example, run `ant build` on the command line
* _mapstruct-on-gradle_: Shows how to use MapStruct in Gradle-based projects; to build the example project, run `./gradlew clean build` on the command line
* _mapstruct-lombok_: Shows how to use MapStruct together with Lombok (with both a Maven `pom.xml` and a Gradle `build.gradle`); to build the example project, run either `mvn clean install` or `./gradlew clean build` on the command line
* _mapstruct-iterable-non-iterable_: Shows how by means of a mapper util class conversions can be made from an iterable- to its non-iterable element
* _mapstruct-mapping-from-map_: Shows how by means of a mapper util class and qualifiers extracting value can be carried out on Maps. Watch [mapstruct/mapstruct#1075](https://github.com/mapstruct/mapstruct/issues/1075) for native support.
* _mapstruct-rounding_: Shows how by means of a mapper util class and qualifiers roundings can be carried out on Numbers
* _mapstruct-examples-updatemethods-1_: Shows how to update an existing target object
* _mapstruct-examples-field-mapping_: Shows how MapStruct can be used with "struct" like objects with public fields
* _mapstruct-nested-bean-mappings_: Shows how to map object graphs via a main root method
* _mapstruct-mapping-with-cycles_: Shows how to map object graphs that can contain cycles
* _mapstruct-spi-accessor-naming_: Example on how to use the Service Provider Interface (SPI) for a custom accessor naming strategy.
* _mapstruct-protobuf3_: Example on how to use protobuf3 with MapStruct
* _mapstruct-kotlin_: Example on how to use MapStruct with Kotlin using KAPT (Kotlin Annotation Processing Tool)
* _mapstruct-kotlin-gradle_: Example on how to use MapStruct with Kotlin and Gradle Kotlin DSL using KAPT
* _mapstruct-jpa-parent-child_: Example on how to use @Context in relation to parent / child relations in JPA)
* _mapstruct-suppress-unmapped_: Shows how mapping to target properties can be ignored without warning by default in a mixed scenario. However bean property mappings that have the same name will still be applied.
* _mapstruct-lookup-entity-with-composed-key_: Shows how an object with composite key can be read from the database in a mapping method.
* _mapstruct-clone_: Shows how an object can be deeply cloned by defining all mapping methods.
* _mapstruct-metadata-annotations_: Demonstrates how to read annotations and use them as mapping instruction.

## License

The examples in this project are licensed under the Apache License, Version 2.0.
