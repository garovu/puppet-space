# Puppet Space

Welcome to the Puppet Space repository! This repository serves as an example for using Puppet to manage your infrastructure.

## Getting Started

To get started with Puppet Space, follow these steps:

1. Clone the repository to your local machine.
2. Install Puppet on your system.
3. Configure your Puppet environment.
4. Run Puppet to apply the desired configurations.

## Repository Structure

The repository is structured as follows:

```shell
puppet-space/
├── manifests/
│   ├── site.pp
│   └── ...
├── modules/
│   ├── apache/
│   │   ├── manifests/
│   │   │   ├── init.pp
│   │   │   └── ...
│   │   └── ...
│   └── ...
├── files/
│   ├── config/
│   │   ├── apache.conf
│   │   └── ...
│   └── ...
└── README.md
```

- The `manifests/` directory contains the main Puppet manifest files, including `site.pp`.
- The `modules/` directory contains individual Puppet modules for managing different components of your infrastructure.
<!-- - The `hiera/` directory contains Hiera configuration files for data separation. -->
- The `files/` directory contains any additional files needed for configuration, such as Apache or MySQL configuration files.

## Contributing

If you would like to contribute to Puppet Space, please follow our [contribution guidelines](CONTRIBUTING.md).

## License

Puppet Space is licensed under the [MIT License](LICENSE).
