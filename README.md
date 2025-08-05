# kind-presence

Project about yoga and things that help you to be friendly and kind.

# deploy infrastructure

- sam build
- sam deploy --config-env prod --parameter-overrides $(cat .params/prod.ini)
