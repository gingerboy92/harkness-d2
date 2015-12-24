# Harkness Kernel #
Harkness is a kernel for d2lte based on Cyanogenmod(CM) source code, named after the [Fallout 3](http://fallout.wikia.com/wiki/Fallout_3) character [Harkness](http://fallout.wikia.com/wiki/Harkness).
This kernel may or may not be a spoiler to the Fallout 3 quest, [The Replicated Man](http://fallout.wikia.com/wiki/The_Replicated_Man).

> _"Self determination is NOT a malfunction"_ -Harkness (Android A3-21)

This kernel contains work from side projects I've been working on, features I use personally & fixes in testing (for upstreaming to CM). Vital fixes & certain features will likely be pushed to http://review.cyanogenmod.org/. Because of this, my working branch will ALWAYS be rebased onto the latest CM. (feel free to request that I upstream a few patchsets)

## Features ##
  * Based on [CyanogenMod's d2 kernel](https://github.com/CyanogenMod/android_kernel_samsung_d2)
  * Compiled with the latest Sourcery CodeBench EABI toolchain (<font color='red'>current:</font> 2014-5.28)
  * Floating-point optimizations for vfp
  * Removed sensor selftests
  * Improvements from [Motorola](https://github.com/MotorolaMobilityLLC/kernel-msm)
    * Re-enabled standalone power collapse (w/ fixes)
    * Improvements to bam\_dmux polling
    * Allow acpuclock to init to max speed
    * Memutils optimizations for MSM8960PRO
    * Improvements/fixes to mem alloc, sched, smp, vfp
  * Modified interactive cpufreq governer for improved power consumption
  * FauxSound
  * FastCharge
  * Simplistic [Barbershop Load Distribution](https://github.com/rmullick/bld-patches/) scheduling algorithm
  * (see [github](https://github.com/SyNtheticNightmar3/CM_Harkness_Kernel/commits/A3-21))

## Release Notes ##
[Release Notes](https://bintray.com/syntheticnightmar3/rivet/d2-harkness-kernel/view/release) can be found on Bintray. Starting after Harkness' first release build, this will be updated to contain a changelog and note any important CM changes that may effect compatibility.

## Downloads ##
[![](https://lh6.googleusercontent.com/-4StbHEKJtpc/U8-doc3hP8I/AAAAAAAAAG0/45m4O8byvLw/s270/Test_builds.png)](https://bintray.com/syntheticnightmar3/rivet/d2-harkness-kernel/test)

**Release builds currently in testing phase**
```
[https://lh6.googleusercontent.com/--UAMuZkcPa4/U8-dmpUoIZI/AAAAAAAAAGs/m6vKe9WYBYE/s270/release_builds.png]
```

Images used from the fallout wiki, Overseer font by http://www.pixelsagas.com/