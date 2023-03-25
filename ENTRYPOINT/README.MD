### ENTRYPOINT

ENTRYPOINT is used to run containers like CMD but we cant override ENTRYPOINT.
where as CMD can be overrided.
If we use CMD and Entrypoint at the same time and dont provide any arguments from terminal
CMD acts as argument provider to ENTRYPOINT
CMD will suppy default arguments to ENTRYPOINT. you will always override CMD arguments from runtime