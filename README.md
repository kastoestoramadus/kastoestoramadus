## Waldemar Wosiński

Senior Scala & Big Data engineer in Warsaw. 15+ years commercial, 10+ in Scala — banking, fintech and public sector.

**What I'm building**

- **[hocon-formatter](https://github.com/kastoestoramadus/hocon-formatter)** — an opinionated formatter for HOCON, in Scala, cross-built to Scala.js. HOCON is a better config format than YAML and still has no formatter.
- **[ekrich/sconfig](https://github.com/ekrich/sconfig)** — contributor. The Scala implementation of HOCON that lets scalafmt compile to a native binary. My work sits in the rendering engine: comment preservation, multipath compaction, round-trip fidelity.
- **[lightbend/config](https://github.com/lightbend/config)** — the Java original, in maintenance mode, yet three of my fixes are merged there: [#866](https://github.com/lightbend/config/pull/866), [#867](https://github.com/lightbend/config/pull/867), [#871](https://github.com/lightbend/config/pull/871). I port bugs between the two codebases in both directions — [sconfig PRs](https://github.com/ekrich/sconfig/pulls?q=is%3Apr+author%3Akastoestoramadus), [lightbend PRs](https://github.com/lightbend/config/pulls?q=is%3Apr+author%3Akastoestoramadus).

I wrote the whole loop up — twin PRs, probes before claims, AI agents that have to earn their statements — in the post [HOCON - a two-way street between sconfig and lightbend/config](https://blog.ww86.eu/dev/2026/10/05/hocon-two-way-street.html).

Lossless round-tripping is the hard prerequisite for a formatter — which is why the renderer work came first.

**Stack** Scala 3 · Spark · Kafka · Databricks · Cats Effect · Akka · Kubernetes · AWS · GCP

[blog.ww86.eu](https://blog.ww86.eu) · waldemar.wosinski@gmail.com
