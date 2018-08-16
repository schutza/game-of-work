# game-of-work
event-stream-based simulation of an organisation

## Ideas

An `organisation` has `employe`s. Many of them.
They are organised in a hierarchy. An `employee` has an `age`, and works for the `organisation` for a finite amount of time (until retirement, until employee leaves, or is fired).
Each `employee`'s `performance`/`output` is influenced by `event`s that happen in the `context` of the employee: `work-events` and `life-events`.
Organisation can be represented visually in near-real-time on dashboards: head-count, workforce, employee data-points aggregations.

## Design

* Event-driven reactive system based on Kafka Streams
* Microservices architecture
* Docker compose
* ELK (Elasticsearch, Logstash, Kibana)
