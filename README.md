# MetaWardsData
This repository contains all of the data (e.g. input parameters, etc.) 
for the MetaWards project. This separates the data needed for a model 
run from the code

## Generating a version file
After cloning the repository, run:

```sh
./version
```
or

```sh
bash version
```

This will create a file called `version.txt` containing a version string 
generated from the Git commit information. This will be read by 
the [MetaWards](https://github.com/chryswoods/MetaWards) program so 
that output data from simulations can be automatically cross-referenced 
with the input data from which they were generated. The version string 
is created from the Git [tag](https://git-scm.com/book/en/v2/Git-Basics-Tagging) 
history. If no tags are present, then the `version.txt` file will not be created.
