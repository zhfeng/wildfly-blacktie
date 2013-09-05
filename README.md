wildfly-blacktie
================

This is a subsystem for the wildfly. 

### Build

    mvn clean install

### Drop to the wildfly

    unzip build/target/wildfly-blacktie-build-8.0.0.Beta1-SNAPSHOT-bin.zip -d /path/to/wildfly-8.0.0-Beta1

### Run with standalone-blacktie.xml

    cp docs/examples/configs/standalone-blacktie.xml standalone/configuration/
    bin/standalone.sh -c standalone-blacktie.xml
