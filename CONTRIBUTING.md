# Contributing guidelines

## How to become a contributor and submit your own code

### Contributor License Agreements

We'd love to accept your patches! Before we can take them, we have to jump a couple of legal hurdles.

Please fill out either the individual or corporate Contributor License Agreement (CLA).

  * If you are an individual writing original source code and you're sure you own the intellectual property, then you'll need to sign an [individual CLA](https://identity.linuxfoundation.org/node/285/node/285/individual-signup).
  * If you work for a company that wants to allow you to contribute your work, then you'll need to sign a [corporate CLA](https://identity.linuxfoundation.org/node/285/organization-signup).

Follow either of the two links above to access the appropriate CLA and instructions for how to sign and return it. Once we receive it, we'll be able to accept your pull requests.

### Contributing A Patch

1. Submit an issue describing your proposed change to the repo in question.
2. The [repo owners](OWNERS) will respond to your issue promptly.
3. If your proposed change is accepted, and you haven't already done so, sign a Contributor License Agreement (see details above).
4. Fork the desired repo, develop and test your code changes.
5. Submit a pull request.

### Building

`kubeadm` uses the same build process as the rest of the `kubernetes/kubernetes` repository.
However, you do not frequently have to build all of kubernetes to work on kubeadm.

See [./vagrant/README.md](./vagrant/README.md) for a quick workflow to build and test your own kubeadm binaries. 🙂

### Adding dependencies

If your patch depends on new packages, add that package with [`godep`](https://github.com/tools/godep). Follow the [instructions to add a dependency](https://github.com/kubernetes/kubernetes/blob/master/docs/devel/development.md#godep-and-dependency-management).
