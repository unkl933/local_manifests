Manifests for EvolutionX Android 12 with kernel 4.4 HMP
=========================================

Copy to .repo/local_manifests directory in your ROM source

Some ROMs dont allow for overriding the QCOM HALs or they don't override the HALs properly.

The most obvious symptom is no graphics when trying to boot a fresh build.

This DT required hardware/qcom-caf/msm8996-LA.UM.9.6.2.r1-04100-89xx.0 directory of your ROM source.

If your ROM not include msm8996-LA.UM.9.6.2.r1-04100-89xx.0 

```bash

# go to directory hardware/qcom-caf
cd hardware/qcom-caf

# clone msm8996-LA.UM.9.6.2.r1-04100-89xx.0
git clone https://github.com/unkl933/qcom-caf -b msm8996-4.4 msm8996-LA.UM.9.6.2.r1-04100-89xx.0

```

That's it :)
