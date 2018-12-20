
1. Run `process-run.py` with the following flags: `-l 5:100,5:100`. What
should the CPU utilization be (e.g., the percent of time the CPU is in use?)
Why do you know this? Use the `-c`and `-p` flags to see if you were right.

```sh
Produce a trace of what would happen when you run these processes:
Process 0
  cpu
  cpu
  cpu
  cpu
  cpu

Process 1
  cpu
  cpu
  cpu
  cpu
  cpu

Important behaviors:
  System will switch when the current process is FINISHED or ISSUES AN IO
  After IOs, the process issuing the IO will run LATER (when it is its turn)

```