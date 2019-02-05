# Orchestrator

ClearMetal runs on a distributed services architecture.  This architecture has various components that need to be synchronized to complete our daily pipeline.  

In order to run this pipeline, we need an orchestrator that can schedule and synchronize tasks to be run.  

Your job is to create this orchestrator.  The guidelines for the orchestrator are:
- You can use whatever tools you want
- A task can be either recurring or one-time
- A task can have dependencies.  For example, TaskABC may need to be executed before TaskXYZ can start
- You should be able to retrospectively check whether a task succeeds or fails (i.e. there should be some sort of monitoring)
- You should be able to easily rerun a task if it fails
- You can design the tasks however you want (i.e. they can be a bash script, a python script, running a docker container, etc…).   
- You should also provide a brief README describing your design choices.  

This is designed to be a fairly open-ended challenge.  We ask that you not spend too much time on it as we are mostly evaluating your thought process and your design choices rather than a fully working framework.
