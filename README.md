## Setup
```
scram project -n "CMSSW_10_6_27_pfnano" CMSSW_10_6_27
cd CMSSW_10_6_27_pfnano/src
cmsenv
git clone git@github.com:DryRun/PFNano PhysicsTools/PFNano
git clone git@github.com:DAZSLE/AK15Nano PhysicsTools/AK15Nano
scram b -j8
```
