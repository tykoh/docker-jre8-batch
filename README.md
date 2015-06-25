# docker-jre8-batch
A docker container to run batch jobs.

## Data container
Mount a data container with directory structure /data/batch

Within the base batch directory (/data/batch), there should exist as shell script, "start.sh" to start all the required batch job

Individual batch job should be placed in different directory under /data/batch.

Example : /data/batch/job1, /data/batc/job2, etc.
