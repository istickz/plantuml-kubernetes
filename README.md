# PlantUML Kubernetes Icons

## Description

This repository contains PlantUML files that utilize icons from the [Kubernetes Community](https://github.com/kubernetes/community/) repository. These icons are used to create visually appealing and informative UML diagrams.

## Features

- A collection of PlantUML files designed for various use cases
- Icons sourced from the Kubernetes Community repository
- Easy-to-read and modify PlantUML source files
- Documentation and examples for using the UML diagrams

## Usage

To use these PlantUML files in your own projects, simply clone the repository and include the desired PlantUML files in your diagrams.

```bash
git clone https://github.com/istickz/plantuml-kubernetes.git
cd plantuml-kubernetes
git submodule update --init --recursive
```

You can then reference the PlantUML files in your diagrams using !includeurl as follows:

```plantuml
@startuml
!define KubernetesPuml https://raw.githubusercontent.com/istickz/plantuml-kubernetes/main/puml/kubernetes-community

!includeurl KubernetesPuml/k8s-pod.puml
@enduml
```

## Contributing

We welcome contributions to this repository! If you have suggestions for improvements, bug reports, or new PlantUML files to add, please follow these steps:

1. Fork the repository by clicking on the "Fork" button at the top right of this page.
2. Clone your forked repository:
    ```bash
    git clone https://github.com/istickz/plantuml-kubernetes.git
    cd plantuml-kubernetes
    ```
3. Initialize and update the submodule:
    ```bash
    git submodule update --init --recursive
    ```
4. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
5. Make your changes and commit them:
    ```bash
    git commit -m 'Add new feature'
    ```
6. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
7. Open a pull request with a detailed description of your changes.

Please ensure your contributions adhere to the coding standards and practices used in this repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

The icons used in this repository are sourced from the [Kubernetes Community](https://github.com/kubernetes/community/) repository, which is licensed under the Apache License 2.0. Please ensure that you comply with the license terms when using these icons in your own projects.

For detailed license information, see the [NOTICE](NOTICE) file.

