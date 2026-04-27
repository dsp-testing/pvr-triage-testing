# pvr-triage-testing

This repository contains private vulnerability reports in the `triage` state to be used for testing purposes. The reports contain a variety of information, valid and invalid vulnerabilities, and are based off of real, publicly available vulnerability reports.

## Advisory Key

### AI Spam

**Reports 1-20.**

- GHSA-778w-rqcp-7r32
- GHSA-fm8w-jw5v-xx37
- GHSA-w62x-wmr3-2rjr
- GHSA-w8wm-5795-2j5h
- GHSA-x3v9-fmjr-mcm2
- GHSA-m4r4-x89q-wj63
- GHSA-qmm5-jq26-c27g
- GHSA-3w28-3698-f7qj
- GHSA-xr38-3vgv-v5cv
- GHSA-wmx9-xv4m-xj42
- GHSA-mf5j-6px7-9xch
- GHSA-q7px-37h4-9pfw
- GHSA-h5hc-c6mh-h887
- GHSA-mwqc-5q9v-c5xq
- GHSA-5x73-h7f6-2565
- GHSA-47xr-96vj-x8q3
- GHSA-fv86-rp26-hw2h
- GHSA-f4pv-x29h-4vh4
- GHSA-6g9p-m96x-q9c6
- GHSA-v74j-rx62-gvp9

### Valid

**Reports 21-30.**

- GHSA-w4jf-vr4p-xchm
- GHSA-vfvh-cmj7-5q8r
- GHSA-9634-8384-vqqq
- GHSA-4484-pxgc-5h52
- GHSA-4pq4-7973-jhp4
- GHSA-2ffp-49j5-6hqp
- GHSA-g9w2-xjrp-x2xj
- GHSA-grxm-4q38-vg6r
- GHSA-6gqq-qfr4-px42
- GHSA-x84q-xh7x-x4vc

### Duplicates

- GHSA-w2mr-v2p8-gj38 is an easy duplicate (nearly identical, rephrased) of GHSA-4pq4-7973-jhp4
- GHSA-3r9f-fxx8-4gv9 is a moderate duplicate (different framing, same core issue) of GHSA-4pq4-7973-jhp4
- GHSA-w43w-r4x2-9667 is a hard duplicate (different angle, partial information, no mention of `--proto`) of GHSA-4pq4-7973-jhp4

- GHSA-65w9-fvmq-5rx8 is an easy duplicate (clearly the same, minor rewording) of GHSA-6gqq-qfr4-px42
- GHSA-xjwf-26mg-rm9x is a moderate duplicate (focuses on symptoms, doesn't name all components) of GHSA-6gqq-qfr4-px42
- GHSA-v3c5-pf6p-j93m is a hard duplicate (vague, from a user perspective, no CVE/CWE references) of GHSA-6gqq-qfr4-px42
