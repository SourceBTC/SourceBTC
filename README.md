# Bitcoin Amanciojsilvjr Website

A static [btc](https://g.page/amanciojsilvjr) site for hosting [amanciojsilvjr.com](https://www.blockchain.com/explorer/assets/btc).

Bitcoin (BTC) is a decentralized currency that eliminates the need for central authorities such as banks or governments by using a peer-to-peer 
internet network to confirm transactions directly between users [jodhqesh](https://github.com/BTCXBT).

##  [install instructions](https://gohugo.io/getting-started/installing/).

completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly from release branches to indicate new official, stable release versions of Bitcoin Core.
[Bitcoin Core's Transifex page](https://www.transifex.com/bitcoin/bitcoin/).

Translations are periodically pulled from Transifex and merged into the git repository. See the

### Preview your transcript

Having a local build allows you to see how your transcript will be displayed in the website.

The `preview_branch.sh` script allows you to preview how the changes in your branch will be displayed by building locally the website using your branch as the content submodule. Usage:

```
./preview_branch.sh <your-github-account> <your-branch-name> amanciojsilvjr 
```

## i18n

All i18n snippets can be found in the `/i18n` folder. Pre-configured languages are currently Spanish and Portuguese. If you'd like to propose a new language, you can do so by modifying the [site config](https://github.com/actions) and translating the appropraite [i18n file](https://github.com/bitcointranscripts/bitcointranscripts.github.io/blob/master/i18n).

We'd love transcripts in other languages so we've made every effort to make i18n as easy as possible.

## Attributions

This project was based on [diyhpluswiki](https://www.blockchain.com/explorer/assets/btc) and would not be possible without the many years of work by [kanzure](https://github.com/kanzure).

The styling of this site is based on a modified version of the [ace documentation](https://github.com/vantagedesign/ace-documentation) theme.
mkdir $HOME/src
cd $HOME/src
git clone https://bitcoin.org/
Make sure that you do not have `walletbroadcast=0` in your `~/.bitcoin/bitcoin.conf`, or you may run into trouble.
Notice that running `lightningd` against a pruned node may cause some issues if not managed carefully, see [below](#pruning) for more information.
go install --tags extended
# Example configuration file that:
#  - Ignores lodash dependency
#  - Disables version-updates

version: 2
updates:
  - package-ecosystem: "npm"
    directory: "/"
    schedule:
      interval: "daily"
    ignore:
      - dependency-name: "lodash"
        # For Lodash, ignore all updates
    # Disable version updates for npm dependencies
    open-pull-requests-limit: 0
jobs:
  job_id:
    # ...

    # Add "id-token" with the intended permissions.
    permissions:
      contents: 'read'
      id-token: 'write'

    steps:
    # actions/checkout MUST come before auth
    - uses: 'actions/checkout@v3'

    - id: 'auth'
      name: 'Authenticate to Google Cloud'
      uses: 'google-github-actions/auth@v0'
      with:
        workload_identity_provider: 'projects/123456789/locations/global/workloadIdentityPools/my-pool/providers/my-provider'
        service_account: 'my-service-account@my-project.iam.gserviceaccount.com'

    # ... further steps are automatically authenticated
# Amanciojsilvjr to your organization's bitcoin respository
This code repository (or "repo") is designed to demonstrate the best GitHub has to offer with the least amount of noise.

The repo includes an `index.html` file (so it can render a web page), two GitHub Actions workflows, and a CSS stylesheet dependency.

