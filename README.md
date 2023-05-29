# HTTP Log Monitoring Console App

a simple console program that monitors HTTP traffic on your machine:

## Requirements

* Python3 & pip3 installed
* Minimal terminal size 145x25

## Install

```
make install
```

## Usage

```
usage: http-monitor [-h] [--file FILE] [--threshold THRESHOLD]
    [--section_expiration SECTION_EXPIRATION]
    [--section_refresh SECTION_REFRESH]

# e.g: http-monitor --file access.log --threshold 100 --section-expiration 120 --section-refresh=10
```

```
usage: http-generator [-h] [--file FILE] [--per_second PER_SECOND]

# e.g: http-generator --file access.log --per-second=100
```
