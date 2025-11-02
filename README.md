Task 1
Configure hostnames and IP addresses on all routers as illustrated in the
network topology.

Task 2
Using interface-based configuration, configure OSPF area 0 on the LAN
segment connecting R1 and R4. To allow for faster convergence, configure
OSPF to detect a neighbor failure within one second. The OSPF Dead
Interval should be set to 1 second. The routers should send four Hellos every
second. Verify your configuration using the appropriate commands.

Task 3
Using interface-based configuration, configure OSPF area 1 between R1 and
R2. This area should be configured as a Totally Stubby area. Verify your
configuration.

Task 4
Using interface-based configuration, configure OSPF area 2 between R2 and
R3. Ensure that this area is able to communicate with the OSPF backbone.
Verify your configuration.

Task 5
To allow for area 2 resiliency, configure your network so that the WAN link
between R1 and R3 is used to allow reachability to and from R3 as well as to
the 150.3.3.0/24 subnet should the WAN link between R2 and R3 fail. You
are permitted to use TWO static routes to complete this task. Test your
solution by shutting down the WAN link between R2 and R3.

Task 6
Configure plain text authentication for the OSPF backbone area. Ensure that
all routing still works following your configuration. Use the password
‘CCNP’ for authentication.
