<p align="center">
<img src="http://raw.github.com/supercowpowers/workbench_data/master/images/big_data.jpg" width=400>
</p>
workbench_data
====

This repository stores a set of 'pointers' to large files that are used either in workbench tests, examples or notebooks. Git is not where you want to store large files, but it is a nice place to communicate, organize and aggregate. So this repository is for organizing and communicating, the links contained within this readme point to public Amazon S3 files.

###Current datasets pointed to by this repository include:

- Packages
  - **[Bro-2.2-Linux-x86_64_flex.deb (9 Meg)](https://s3-us-west-2.amazonaws.com/workbench-data/packages/Bro-2.2-Linux-x86_64_flex.deb):** 
  Debian package for Bro. In general the Bro debian package files are WAY too locked down with dependencies on exact versions of libc6 and python2.6. This is a more 'flexible' version.
    
    `wget https://s3-us-west-2.amazonaws.com/workbench-data/packages/Bro-2.2-Linux-x86_64_flex.deb`

- Memory Images
  - **[examplar4.vmem (256 Meg)](https://s3-us-west-2.amazonaws.com/workbench-data/memory_images/exemplar4.vmem):** The memory image is used in the [JPH Security Blog](http://jphsecurity.blogspot.com/2012/01/developing-baseline-approach-to.html) that outlines a nice 'Baseline Approach' to memory forensics. Resources like this are terrific and greatly appreciated by us and the community.
    
    `wget https://s3-us-west-2.amazonaws.com/workbench-data/memory_images/exemplar4.vmem` 
