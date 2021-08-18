# CBL-Mariner 1.0.20210807-1.0 (July 2021 update) Unofficial ISO

You'll find the ISO image attached to this release, with its SHA256 sum in the release text itself. This build is **unofficial** and **not endorsed by Microsoft**. The source code this ISO was built from is also attached, for archival reasons.

Official tag this ISO was built from:
https://github.com/microsoft/CBL-Mariner/releases/tag/1.0.20210807-1.0

## SHA256 Sums

cbl-mariner_full-july-2021-update-1.0.20210818.0515.iso:<br>
1D8630C5B4ADC5EC6110220A0CBAA5EDC524BC4CDFE83F0A88DE0DFC5765C5E8

## Archived Changelog

This changelog was written by jslobodzian I assume, as they published the [release it was copied from](https://github.com/microsoft/CBL-Mariner/releases/tag/1.0.20210807-1.0). It's being archived here for preservation reasons.

"Update kernel to 5.10.52.1

- Enable CONFIG_PROC_EVENTS
- enable legacy /dev/mcelog
  Add new microsoft repo to images. DotNet Core now available in separate Microsoft "internal partner team" repo
  Add cronie and logrotate to images, add systemd timer
  Add SELinux (Permissive Mode supported, but not enabled by default)
  Add dpdk perl-App-cpanminus hyperscan and dependencies to Mariner OS

Fix FIPS LRNG concatenation bug in OpenSSL
Fix issue where selected disk not reflected correctly in partition edit screen of ISO Installer

Update moby-containerd to version 1.4.4
Update swig to 4.0.2

CVE-2015-9541
CVE-2018-19787
[CVE-2019-18874](https://github.com/advisories/GHSA-qfc5-mcwq-26q8)
CVE-2020-0570
[CVE-2020-10108](https://github.com/advisories/GHSA-h96w-mmrf-2h6v)
[CVE-2020-10109](https://github.com/advisories/GHSA-p5xh-vx83-mxcj)
CVE-2020-13962
[CVE-2020-27783](https://github.com/advisories/GHSA-pgww-xf46-h92r)
[CVE-2021-28957](https://github.com/advisories/GHSA-jq4v-f5q6-mjqq)
CVE-2021-3274
CVE-2021-3445
CVE-2021-3546
CVE-2021-22922
CVE-2021-22923
CVE-2021-22924
CVE-2021-22925
CVE-2021-32760
CVE-2021-33503
CVE-2021-33910
CVE-2021-35942
CVE-2021-32740
CVE-2021-36373
CVE-2021-36374"