# Go RabbitMQ Client Library over Tor Network

This is an AMQP 0.9.1 client with RabbitMQ extensions in Go. This library is special use for AMQP over Tor Network.

## Supported Go Versions

This library supports two most recent Go release series, currently 1.8 and 1.9.


## Supported RabbitMQ Versions

This project supports RabbitMQ versions starting with `2.0` but primarily tested
against reasonably recent `3.x` releases. Some features and behaviours may be
server version-specific.

## Goals

Provide a functional interface that closely represents the AMQP 0.9.1 model
targeted to RabbitMQ as a server over Tor Network.  This includes the minimum necessary to
interact the semantics of the protocol.

## Usage

See the 'examples' subdirectory for simple producers and consumers executables.
If you have a use-case in mind which isn't well-represented by the examples,
please file an issue.

## Documentation

Use [Godoc documentation](http://godoc.org/github.com/streadway/amqp) for
reference and usage.

[RabbitMQ tutorials in
Go](https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/go) are also
available.

## Desclaimer

This project is forked from [github.com/streadway/amqp](https://github.com/streadway/amqp). I just use it for my AMQP over Tor Network project, if you have same project as me you can use it.

## License

BSD 2 clause - see LICENSE for more details.


