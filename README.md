# jmh
JMH benchmark

# Setting up the project:
mvn archetype:generate \
          -DinteractiveMode=false \
          -DarchetypeGroupId=org.openjdk.jmh \
          -DarchetypeArtifactId=jmh-java-benchmark-archetype \
          -DgroupId=org.javaclub \
          -DartifactId=jmh \
          -Dversion=1.0

# Building the project:
mvn clean install

# Running the project:
java -jar target/benchmarks.jar

# Benchmark command line options:
java -jar target/benchmarks.jar -h
