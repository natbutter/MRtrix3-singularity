# MRtrix3-singularity
Container for building and running MRtrix3 in a singularity and docker cotainer

Run with, for example:

```
singularity exec mrtrix.img mrconvert
```

To build this image I issued the command (on the singularity recipe attached):

```
sudo singularity build --writable mrtrix.img mrtrix_scratch.sing
```
