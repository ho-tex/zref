# Changelog
All notable changes to the `zref` package since the 
2022-03-08 will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
this project uses date-based 'snapshot' version identifiers.

## [2022-03-29]

### Fixed
 - Avoid that amstext undoes the stepcounter patch in zref-page,
   https://github.com/ho-tex/zref/issues/11
 - Make the unique counter more robust when includeonly is used,
   https://github.com/ho-tex/zref/issues/10
