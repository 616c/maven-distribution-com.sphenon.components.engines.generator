## maven-distribution-com.sphenon.components.engines.generator

# Build [OO Generator](http://oogenerator.org) Distribution from Sphenon components.

## Prerequisites

[Clone and build the Sphenon components](https://github.com/616c/maven-aggregator-com.sphenon).

## Cloning and building

`git clone https://github.com/616c/maven-distribution-com.sphenon.components.engines.generator.git
mvn install`

After successful build, you find distribution archives in the target subfolder, named:

`oogenerator-#.#.#-bin.(tar.gz|tar.bz2|zip)`

## Running

under

`src/test/script/run.bash`

you'll find a little testscript that invokes the generator with full classpath from this project here.
It prints out usage information. Many sample templates can found on [oogenerator.org](http://oogenerator.org).
