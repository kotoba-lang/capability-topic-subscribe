# capability-topic-subscribe

Atomic authority package for `topic/subscribe`.

- imports: `#{:topic-take :topic-poll :topic-count}`
- effects: `#{:ipc-read}`
- default policy: `:autonomous`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
