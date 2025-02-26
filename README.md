[![Build Status](https://github.com/basepom/duplicate-finder-maven-plugin/workflows/ci/badge.svg)](https://github.com/basepom/duplicate-finder-maven-plugin/actions?query=workflow%3Aci)[![Latest Release](https://maven-badges.herokuapp.com/maven-central/org.basepom.maven/duplicate-finder-maven-plugin/badge.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.basepom.maven%22%20AND%20a%3A%22duplicate-finder-maven-plugin%22)


# duplicate-finder Maven plugin

A maven plugin to find and flag duplicate classes and resources on the java classpath.

This ensures stability and reproducability of a maven build and will flag possible problems or conflicts with dependencies in a project.

## About

This plugin is a friendly fork (same main authors) of the [Ning maven-duplicate-finder plugin](https://github.com/ning/maven-duplicate-finder-plugin). It is configuration compatible to the ning plugin; the only change required is the group and artifact id of the plugin itself.

## Requirements

The plugins requires Apache Maven 3.x.x.

Starting with release 1.2.0, Java 7 or better is required.

Starting with release 1.3.0, Java 8 or better is required.

Starting with release 1.5.0, Java 8 or better is required to run the plugin and Java 9 or better (Java 11 strongly recommended) is required to build the plugin.

## Goals

The plugin has two goals:

* `duplicate-finder:check` - the main goal of the plugin. Runs duplicate check on the maven classpaths.
* `duplicate-finder:help` - displays standard maven plugin help information.

## Documentation

Up-to-date documentation is available from the [duplicate finder plugin Wiki](https://github.com/nbauma109/duplicate-finder-maven-plugin/wiki). A snapshot from the last release of the plugin is available in the `docs` folder in this repository.

## Release Notes

See the [Changelog](CHANGES.md).
