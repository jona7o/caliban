# Examples

To run the examples without the rest of the project, add this to your build.sbt:

```scala
libraryDependencies ++= Seq(
  "com.github.ghostdogpr" %% "caliban" % "0.3.1",
  "com.github.ghostdogpr" %% "caliban-http4s" % "0.3.1",
  "com.github.ghostdogpr" %% "caliban-cats" % "0.3.1"
)
```

Run `ExampleApp` and open [http://localhost:8088/graphiql](http://localhost:8088/graphiql)
