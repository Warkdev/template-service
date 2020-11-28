# Mangos-service-archetype

This project is a maven template used to generate the maven archetype to develop Mangos REST API Services.

# How to use it ?

Some simple steps, clone the repo, install the maven package and generate a project based on it !

```sh
# First, install the archetype
git clone https://github.com/Warkdev/mangos-service-archetype.git/
cd mangos-service-archetype
mvn install

# Then, create a new project
cd..
mvn archetype:generate -DarchetypeGroupId=eu.getmangos -DarchetypeArtifactId=mangos-service-template-archetype -DarchetypeVersion=1.0 -DgroupId=eu.getmangos -DartifactId=my-mangos-service -DmainEntity=Test

# This will create a new folder my-mangos-service and generate the basic skeleton around the entity 'Test'

```