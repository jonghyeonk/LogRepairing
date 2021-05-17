# LogRepairing

This repository shows developed algorithm of TBCTBC
The algorithm of online anomaly detection is coded using statistical package R as seen in folder "code" and it calculates anomaly score for each case in trace level and designs the anomaly score for online setting. 

## Prepared Data1 - 5 artificial logs
We used 5 types of process models including small, medium, large, huge, and wide refered from [1] to generate artificial logs. 

## Prepared Data2 - 2 real-life logs
For the real life logs, we consider the Hospital Billing event log containing events about the billing of medical services that have been obtained from the financial modules of the ERP system of a regional hospital, and the Road Traffic event log TBCTBC.

For all logs, we injected 5 types of anomaly patterns including "insert", "skip", "moved", "replace", and "rework" introduced in [2]. The statistics of datasets are summarised in Table XXX in our paper.


## R-files
- TBCTBC

&#x1F53A; Be careful to correctly set your working directory for each R file as uploaded files contain my own local directory.


## References
[1] Nolle, T., Luettgen, S., Seeliger, A., & Mühlhäuser, M. (2019). Binet: Multi-perspective business process anomaly classification. Information Systems, 101458.

[2] TBCTBC
