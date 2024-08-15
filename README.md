# imageOmg
> build your image inside cluster, use your image inside cluster. Basically, it is a P2P Image registry and a P2P build system

## Introduction

most of the time, we build our outside cluster, and then push to image registry, then pull to the cluster to run, obviously, it is not efficient.
to eliminate the time of image pushing and pulling, we can build our image inside the cluster, and share it inside the cluster using P2P-based file distribution.

![alt][arch]


[arch]: img/arch.svg