# New project

* Create argo-resource
* Create helm-deployment
* Port environments (k get pods -o yaml kundereplika-6576ff5874-8t52b| extract_envs)
* Check for
  * Secrets - add to secrets.txt and copy secrets (example: just --justfile ../Justfile copy-secret 00-test kundereplika-tst kundereplika database-credentials)
  * External connection (map in readme.md)
  * Prometheus
  * PVC
  * Gatekeeper
  * Custom timeouts