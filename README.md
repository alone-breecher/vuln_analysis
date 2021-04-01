# vuln_analysis

This tool is created as a part of learning shell scripting, now I am making various changes to make it a better tool which can be used to collect various information of a website.
# Current features

  - Can collect subdomains of a website
  - Can collect CNAME record of the subdomains
  - Can Check for Clickjacking vulnerability

### Installation

```sh
$ git clone https://github.com/alonebreecher/vuln_analysis
$ cd vuln_analysis
$ ./install.sh
```


### Usage

```sh
$ ./sub_domain-collector.sh -h
$ ./sub_domain-collector.sh -d domain_name
```


### To check for clickjacking vulnerability

```sh
$ ./clickjacking.sh URL

Eg : ./clickjacking.sh https://example.com
```
