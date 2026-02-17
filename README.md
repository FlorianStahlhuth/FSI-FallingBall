# FSI-FallingBall
We consider a falling elastic ball in a Newtonian fluid and model its movement via a variational monolithic formulation in the Arbitrary Lagrangian Eulerian Framework. The fluid equations are transformed into the reference configuration by means of the ALE mapping and are coupled to the solid equations therein. To construct the ALE mapping, we utilize a harmonic mesh motion PDE with a control parameter for improved mesh quality. The discretization is based on the Rothe method, i.e. first finite differences in time, then Galerkin finite elememts in space. We deal with the remaining nonlinearities with a Newton-like method, in which the Jacobian is constructed by explicit calculation of the directional derivative.  The implementation is realized with the finite element library deal.II. The parameter file suggests exemplary problem data, but we encourage to experiment with different settings.

The underlying open-source finite element library is <br/>
https://dealii.org <br/>
The latest version of this code is based on deal.II version 9.6.2 (Feb 2026).

