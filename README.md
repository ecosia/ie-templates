# Ecosia IE Domain Administration Templates

This repository includes configuration files that can be used to create Active Directory policies that will set Ecosia as the default search engine for Internet Explorer.

## Usage

For detailed instructions on how to use this repository to install Group Policies for your Active Directory domain, please see [our knowledge base article](https://ecosia.zendesk.com/hc/articles/211813325).

## Directory structure
```
adm/                                       // Classic Administrative Templates
    ├── SearchProviderEcosia.adm           // Provides Ecosia as search engine
    ├── SearchProviderEcosiaBing.adm       // Provides Ecosia and Bing as search engines
    └── SearchProviderEcosiaBingGoogle.adm // Provides Ecosia, Bing and Google as search engines
