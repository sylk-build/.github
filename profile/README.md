# Sylk

Sylk is a free and open-source framework for developing microservices projects. It aims to simplify the process of creating distributed systems using the latest "Battle Tested" technologies.

Features
Some of the key features of Sylk include:

HTTP2-based communication protocol
- Protobuf-based message serialization and deserialization
- gRPC-based code generation for services and clients
- Support for schema evolution and compatibility
- Command-Line Interface for generating resources, implementing server-side logic, and interacting with services

## Getting Started

To get started with Sylk, you can use the [CLI](https://github.com/sylk-build/sylk) to create a new project and generate resources. Here's an example of how to create a new project:

```sh
sylk new my-project
cd my-project
```

Once you've created a project, you can use the CLI to generate resources, such as services and packages. Here's an example of how to generate a new package and service:

```sh
sylk generate package
sylk generate service
```

After you've generated a service, you can implement server-side logic and client-side code to interact with the service.

```sh
sylk run
```

## Contributing
If you're interested in contributing to Sylk, please see our contribution guidelines. We welcome contributions of all kinds, from bug reports to feature requests to code contributions.

## License
Sylk is licensed under the MIT License.
