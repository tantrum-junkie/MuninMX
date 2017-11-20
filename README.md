# MuninMX
MuninMX - A munin frontend and backend replacement as open source AS IT IS!

This repository contains only the Backend Collector! For the Frontend go to:

https://github.com/flyersa/MuninMX-Frontend


# Additions by tantrum-junkie

Build with 

gradle fatJar


All configuration files are provided in conf/ directory.
Make your changes to the config-example.xml file and save it as config.xml
Then place all files in the same directory as the JAR file and start with

java -jar MuninMX-all-1.0.jar config.xml

