<!-- ghmig:moved -->
> **This repository has moved to [https://git.navicore.tech/navicore/triples-lab](https://git.navicore.tech/navicore/triples-lab).**
>
> The GitHub copy is archived and no longer maintained.

Triples Lab
-----

Scratch Project to Explore Banana RDF

### Build and run

```console
sbt assembly
java -jar target/scala-2.12/TriplesLab.jar
```

### Test and Code Coverage

```console
sbt clean coverage test
sbt coverageReport
open target/scala-2.12/scoverage-report/index.html
```

### Code Stats

```console
sbt stats
```
### Check dependencies

```console
sbt dependencyUpdates
```