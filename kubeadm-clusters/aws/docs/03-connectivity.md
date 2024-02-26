# Connectivity

In this lab, you will access the kubernetes nodes by SSH from `student-node` which you should now be logged into.

Check each one

```bash
ssh controlplane
```

```bash
ssh node01
```

```bash
ssh node02
```

Remember to `exit` back to `student-node` each time. ssh access is not configured *between* nodes. This is standard practice when setting up networks, to have one node from which you can get to all the others.


Next: [Node Setup](../../generic/04-node-setup.md)<br>
Prev: [Compute Resources](02-compute-resources.md)