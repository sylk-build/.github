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

## Products
- [Sylk CLI](https://github.com/sylk-build/sylk) - Main feature of sylk. Open source CLI to create, manage and deploy micro-services.
- [Sylk Cloud](https://app.sylk.build) - Sylk Cloud Platform. Feature rich UI to create and manage remote projects.
- [Sylk Docs](https://github.com/sylk-build/docusaurus-sylk) - Docusaurus plugin for generating documentation site for sylk's projects.

## Contributing
If you're interested in contributing to Sylk, please see our contribution guidelines. We welcome contributions of all kinds, from bug reports to feature requests to code contributions.

## License
Sylk is licensed under the MIT License.
