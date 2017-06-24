# generic-ssm

KiCAD files to be used as a template when creating sub-system specific
PCBs.

## Instructions on using this repository as a template

First, clone this repository. Next, install [homebrew](https://brew.sh/) and run

```
$ brew install rename
```

In the root directory, run

```
$ ls . | rename -vs generic YOUR_SUBSYSTEM_NAME
```

For example, `rename -vs generic coms` creates files
`coms_ssm.kicad_pcb`, `coms_ssm.pro` and `coms_ssm.sch`.

Next, delete this git repository by running

```
$ rm -Rf .git/
```
