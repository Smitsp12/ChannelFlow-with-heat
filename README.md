# ChannelFlow-with-heat
Problem description: To get velocity and temperature field within the channel flow. 

Here, the temperature boundary condition is given at walls of the domain. To get the temperature field, generalized heat equation is discritized, including viscous dissipation, advection, diffusive and pressure terms. The steps followed are as follows:
  1) Get the velocity field from vorticity streamfunction formulation as used in CavityFlow repository.
  2) Use this velocity field to get pressure field from pressure poission equation.
  3) get the temerature field from discretized heat equation.
