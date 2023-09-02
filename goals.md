I want to:
  - build an app that publishes to a kafka topic (pub-app)
  - build another app that consumes from that same kafka topic (cons-app)
  - deploy the following through argocd:
    - kafka
    - pub-app
    - cons-app

No security or user accounts will be present at the start

Further goals:
  - integrate argocd with a git pipeline
  - retrieve some secret values from a vault
  - aggregate logs
