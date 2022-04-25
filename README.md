# HelloWorld gRPC API sample client and server

A sample to demonstrate how to consume gRPC API definition (`.proto` file) from a separate project.

## Building

```console
$ cargo build
```

## Running

Run server:
```console
$ ./target/debug/helloworld-server &
```

Run client:
```console
$ ./target/debug/helloworld-client
```

Stop server:
```console
$ fg
<CTRL-C>
```