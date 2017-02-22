IPC - Invasion Percolation Cluster
==================================
Invasion percolation is a stochastic growth model introduced by Wilkinson and
Willemsen.  Assume G is a graph and \rho is a designated vertex (the "root"),
and assign to each edge of G a random weight, uniformly sampled from [0,1].
Let I\_0 (the cluster at time 0) be the set containing the root only, and let
I\_{n+1} be obtained from I\_n by adding the external vertex which touches the
lightest edge on the edge boundary of I\_n.

This process results an infinite cluster (given that G was infinite).  In this
module we simulate its behaviour in finite time.
