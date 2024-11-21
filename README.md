# NGT-Task-3.3

## Installing CMSSW

```
cmsrel CMSSW_14_0_11
cd CMSSW_14_0_11/src
cmsenv

```

## Tracker Analyzer

```
git clone https://github.com/vmuralee/PREanalysis.git -b <your branch>
cd PREanalysis/TrackAna
scram b -j 32
```

## Running Analyzer

```
cmsRun python/Trackanalyzer_cfg.py 
```
