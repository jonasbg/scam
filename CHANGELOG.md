# Changelog

## [0.2.0](https://github.com/jonasbg/scam/compare/v0.1.0...v0.2.0) (2026-06-16)


### 🚀 Features

* add callcenter URL configuration and implement logging capture for periodic data push ([5b8fab9](https://github.com/jonasbg/scam/commit/5b8fab9b29d83bb389596a5599442221ffdc0800))
* add comprehensive documentation for operator functionality and architecture ([0fe6dc6](https://github.com/jonasbg/scam/commit/0fe6dc62f011516192fd28aac807b4d08d8dcf0d))
* add decision log for spam-operator rollout and document auth model considerations ([4c95b6e](https://github.com/jonasbg/scam/commit/4c95b6e5840a3be4096d2e27be845b1e2cb2d494))
* add devcontainer lock file and update Dockerfile with specific image digest ([9f28354](https://github.com/jonasbg/scam/commit/9f283546568108189632ea44d4000d0942aad452))
* add initial Helm chart structure for spam-agent including deployment, RBAC, and values configuration ([2546fee](https://github.com/jonasbg/scam/commit/2546feeb564b28164acaef9c306f67cc03a510a2))
* add ReplicaSet informer and enhance pod owner resolution logic ([4e800e3](https://github.com/jonasbg/scam/commit/4e800e34e497ea54aeeb77a2ab622ac5c4a7c67b))
* add spam-operator Kubernetes operator ([572e8a5](https://github.com/jonasbg/scam/commit/572e8a556b5a36b6b75c31d1875f82ffe7c2fa8a))
* add startup banner with cluster metadata on stderr ([66f4404](https://github.com/jonasbg/scam/commit/66f4404e9a8198ed916df1dc1d0b801cea96575f))
* add support for Gateway API resources and enhance RBAC permissions ([1dadf5c](https://github.com/jonasbg/scam/commit/1dadf5c4cdf4c9f8d9b892577ddeb5d746d1c37d))
* drift-resistant snapshot reconcile + ACK protocol for SPAM ingest ([78af12c](https://github.com/jonasbg/scam/commit/78af12c1db65cb9112bc9f8376a1f49298419d23))
* dynamically determine container registry based on GitHub server URL ([4929fbb](https://github.com/jonasbg/scam/commit/4929fbb492ea9f54815a1562cb57833921a8b25c))
* emit all services including unreferenced ClusterIPs ([c690873](https://github.com/jonasbg/scam/commit/c6908733bdca41cd42aa0500576b0b50a95682d1))
* emit liveness heartbeat so quiet clusters stay visible ([f606c92](https://github.com/jonasbg/scam/commit/f606c921851f76309b57bcf2def4921fb8428248))
* enhance backend indexing for Ingress and Traefik routes with new index functions ([8b93cc9](https://github.com/jonasbg/scam/commit/8b93cc9d955c50d337a90a089e69832a4dc58438))
* enhance cluster ID retrieval with fallback to kube-system namespace UID ([6648889](https://github.com/jonasbg/scam/commit/66488890f1fb10afe13cd2047428a2a6c12f5fbc))
* enhance Docker build workflow with cache output handling ([ef6e263](https://github.com/jonasbg/scam/commit/ef6e263288f8c2c8b681fde1d70d112a3b4561a4))
* enhance pod status handling by incorporating phase checks in samePodImages and emitPod functions ([b8dd599](https://github.com/jonasbg/scam/commit/b8dd599933d45479044c00623a2d655236f65e40))
* event_id counter and ACK-driven reconcile snapshot ([05b9910](https://github.com/jonasbg/scam/commit/05b9910f0a3e2365a123e6f212650e02da435388))
* exercise release-please pipeline (fork test) ([55f62bc](https://github.com/jonasbg/scam/commit/55f62bc9f8eb36eac705ff3659ee040572f0bc98))
* full-state snapshots across all tracked kinds with BEGIN/END envelope ([9f6113d](https://github.com/jonasbg/scam/commit/9f6113d75e525bffab30d9e57f3512b116c63a25))
* implement DELETE event handling for Pods, Services, Ingresses, IngressClasses, Gateway APIs, and Traefik routes ([4f405e4](https://github.com/jonasbg/scam/commit/4f405e432968688e49141e0c1a316a3f6c990771))
* periodic ROR identity re-resolve + code review fixes ([#3](https://github.com/jonasbg/scam/issues/3)) ([64713d0](https://github.com/jonasbg/scam/commit/64713d028fe40a7ed3eff2c2fdd0a19ae18d33f7))
* refactor event handlers and introduce utility functions for improved code clarity and maintainability ([4d4f446](https://github.com/jonasbg/scam/commit/4d4f446fe3c8cb2397094539cd42abb3fe3e57d8))
* rename spam-operator to spam-agent and update related configurations ([94dbefb](https://github.com/jonasbg/scam/commit/94dbefb16b1fe602d4eeab3d420d487795eee05b))
* restructure spam-operator to scam, including Helm chart, deployment, RBAC, and documentation updates ([5bea147](https://github.com/jonasbg/scam/commit/5bea147a1186f564927064a594ed5bd60a32002f))
* trim cluster metadata to cluster, cluster_id, and environment ([755569f](https://github.com/jonasbg/scam/commit/755569f597da664dac7e7c7da9ecfe3e48474d1d))
* update authentication method for Docker and Helm registry logins to use secrets ([f2e51a2](https://github.com/jonasbg/scam/commit/f2e51a27a1e2ac59bd547366ba3d09af16d66fbd))
* update callcenter URL configuration and enhance startup logging ([a030f25](https://github.com/jonasbg/scam/commit/a030f25491020e16b2b03fc6b5c95059d4c9f845))
* update dependencies in go.mod for improved compatibility and performance ([dc004bb](https://github.com/jonasbg/scam/commit/dc004bb08c78c17c5c104bdd5d908f4269f73067))
* update devcontainer configuration for improved Go environment setup ([5c0e0ec](https://github.com/jonasbg/scam/commit/5c0e0ec1bc4b1998724a10c4231fff9cd66e030a))
* update Dockerfile and enhance Traefik support with new CRDs and dynamic informers ([11a0165](https://github.com/jonasbg/scam/commit/11a01654e168fbe03e465ed53812ff7691c3bd15))
* update Helm chart handling to use OCI artifact name and streamline versioning ([a99b069](https://github.com/jonasbg/scam/commit/a99b0698bfd2b57f0f1c1ffc042664c640ea40b9))
* update image references to use ghcr.io for scam deployment and related configurations ([7e460c7](https://github.com/jonasbg/scam/commit/7e460c7dbfe8bf45be37e59c131014030a5397f0))
* update storage model to use JSONB-first approach and define views for dynamic schema handling ([e77533f](https://github.com/jonasbg/scam/commit/e77533fa747231aa6d8b044530c0ba63a7d65af2))
* watch EndpointSlices for external service IP visibility ([c9d095f](https://github.com/jonasbg/scam/commit/c9d095fc44fad0a20a7b1326185d2115760b92d7))


### 🐛 Bug Fixes

* add namespaces resource to ClusterRole for improved RBAC permissions ([8193e54](https://github.com/jonasbg/scam/commit/8193e54f65eaf4af7ff4e81ef0d5b10abd964ab1))
* add non-root runAsGroup to satisfy require-non-root-groups policy ([a21a140](https://github.com/jonasbg/scam/commit/a21a140f0f7726f6bd32f62cc27bd0cc807881cb))
* add replicasets RBAC permission for pod owner resolution ([39f676b](https://github.com/jonasbg/scam/commit/39f676b54a0a3e3fc2201d200f62e6cf3b11edff))
* emit SNAPSHOT key list on startup so restart drift clears immediately ([9ef0d1e](https://github.com/jonasbg/scam/commit/9ef0d1ebfce46cd3a60e427f3f0425a669a676ff))


### ♻️ Refactoring

* restructure into Go package layout and fix workload_count ([4638ecd](https://github.com/jonasbg/scam/commit/4638ecdb28c5bae4ec4f3cf12f3e940089d21872))


### 🤖 CI

* automate releases with release-please ([dfdf6c5](https://github.com/jonasbg/scam/commit/dfdf6c5234092e9d93fc8ab2bf37891f10398ae8))
* gate helm-push to main only ([5ffbca5](https://github.com/jonasbg/scam/commit/5ffbca59c94ea5f6cfed379790e3f4d5bb81fc98))
