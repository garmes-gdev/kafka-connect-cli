# kafka-connect-cli
Kafka connect command line interface (CLI) around the Kafka Connect REST Interface to manage connectors.
## Usage

```
  Command: list
  list active connectors names.

  Command: get
  get the configuration of the specified connector.

  Command: delete
  remove the specified connector.

  Command: create
  create the specified connector with the config from stdin; the connector cannot already exist.

  Command: run
  create or update the specified connector with the config from stdin.

  Command: status
  get connector and it's task(s) state(s).

  Command: plugins
  list the available connector class plugins on the classpath.

  Command: config
  list the configurations for the specified connector.

  Command: pause
  pause the specified connector.

  Command: restart
  restart the specified connector.

  Command: resume
  resume the specified connector.

  Command: validate
  validate the connector config from stdin against a connector class plugin on the classpath.

  Command: backup
  Create a configuration backup for all connectors.

```

