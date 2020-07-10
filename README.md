# DITA-OT plugin project sample
------------------------

[![license](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)

## Description
This is intended to be a sample startup project for developers that need to develop and package plugins in a DITA-OT ready to be used.

## The contents of this project
- pom.xml: The Maven project file
- assembly.xml:	Controls the packaging of the project into a final ZIP containing the DITA-OT ready to be used
- /plugins: Directory which contains DITA-OT plugins that will be installed in the final packaged DITA-OT

## Pom properties
- ditaot.version: version of the DITA-OT used for packaging

## How to build the project
Using the following command on Windows: `mvn package`

Note: This will create a ZIP file from the target directory. This package can be unziped where DITA-OT should be used.
