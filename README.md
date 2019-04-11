
# SHWAP-Template

[Software Heritage](https://www.softwareheritage.org) Acquisition Process skeleton template.

This repository should define the skeleton of directories to clone for a specific SHWAP (for each software acquisition).

The tree of directories reflects the SHWAP workflow, as follows: 

**.**
**├── 0 - Origin**
           Where (a digital copy of) the original matherial is collected in its raw format. Also the **AcSWnotice** is stored here.

**├── 1 - Warehouse**
           Where matherials are transformed.

**├── 2 - Depository**
           Where  matherials curated and enriched (**DepositedSC**).

**└── 3 - Vault**
            Where curated matherial (**CuratedSC**) are stored in their final form, ready to be stored in Software Heritage.

More details can be found in the README of each directory.

The SHWAP for a specific software source code should begin with a fork of this repository.
