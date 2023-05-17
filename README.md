## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add diffgram https://diffgram.github.io/diffgram-helm/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
diffgram` to see the charts.

To install the diffgram chart:

    helm install diffgram diffgram/diffgram

To uninstall the chart:

    helm delete diffgram