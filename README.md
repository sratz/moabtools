# MOAB Tools

These tools simplify working with the job submission system of the Moab Cluster Suite.


## msubwrapper

This can be used to quickly submit a job to the cluster without the need to
create a submission script.

### Usage:

    msubwrapper [msub_options [msub_options...]] <command> [options [options ...]]

### Example:

    msubwrapper -l walltime=01:00:00 -N "compilation" make -j8


## mtop

Shows a list of all users and the number of processors they are using, sorted by the latter.
