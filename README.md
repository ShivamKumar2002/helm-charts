# Personal Helm Charts Repository

Welcome to my personal collection of Helm charts. These charts are designed to streamline the deployment of various applications and services to Kubernetes clusters. Feel free to use and contribute to this repository to make it even more useful.

## About Helm

[Helm](https://helm.sh/) is a package manager for Kubernetes that allows you to define, install, and upgrade even the most complex Kubernetes applications. Helm charts are collections of files that describe a related set of Kubernetes resources. For more information about Helm, visit the [official documentation](https://helm.sh/docs/).

## Charts Available

This repository contains the following Helm charts:

- `browserless`: A chart to deploy [Browserless](https://github.com/browserless/browserless) browser automation tool. See [browserless-helm-chart](https://github.com/ShivamKumar2002/browserless-helm-chart) for more details.

- `big-agi`: A chart to deploy [Big-AGI](https://github.com/enricoros/big-AGI) Generative AI Suite. See [big-agi-helm-chart](https://github.com/ShivamKumar2002/big-agi-helm-chart) for more details.

- `linkwarden`: A chart to deploy [Linkwarden](https://github.com/linkwarden/linkwarden). See [linkwarden-helm-chart](https://github.com/ShivamKumar2002/linkwarden-helm-chart) for more details.


## Prerequisites

- Kubernetes 1.20+
- Helm 3.0+


## Getting Started

### Add the Repository

To add this repository to your Helm client, run the following command:

```shell
helm repo add shivam-charts https://shivamkumar2002.github.io/helm-charts/
```

### Update the Repository

To update the charts in your local Helm client, run:

```shell
helm repo update
```

### Search for Charts

To search for charts within this repository:

```shell
helm search repo shivam-charts
```

### Install a Chart

To install a chart, use the `helm install` command:

```shell
helm install my-release shivam-charts/chart-name
```

Replace `my-release` with the name you want to assign to your release, and `shivam-charts/chart-name` with the chart you want to install.


## Configuration

Each chart has its own `values.yaml` file that contains the default configuration settings. You can customize these settings by providing your own `values.yaml` during installation or upgrade:

```shell
helm install my-release shivam-charts/chart-name --values my-values.yaml
```

## Contributing

Contributions are welcome! If you have a chart you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your chart.
3. Add your chart to the `charts` directory.
4. Update the `Chart.yaml` with the necessary metadata.
5. Commit and push your changes.
6. Submit a pull request to this repository.

Please read `CONTRIBUTING.md` for details on our code of conduct and the process for submitting pull requests.


## Contact

If you have any questions or feedback, please reach out to me at:

- GitHub: [@ShivamKumar2002](https://github.com/ShivamKumar2002)
