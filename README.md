# EZID
Scripts for working with EZID ARK service.

Uses python 2.7, because that is what Apple provides on OS X be default.

We predominately use csv-update.py as it allows for minting and updating
ARKs using a tab-delimited source file.

Requires:
  - [SUDS](https://github.com/suds-community/suds) (`sudo pip install suds`)
  - [Requests](https://docs.python-requests.org/en/latest/) (`sudo pip install requests`)

To batch download all of your ARKs with certain fields of interest, please use the EZID provided script [batch-download.sh](https://github.com/CDLUC3/ezid-client-tools/blob/master/batch-download.sh).