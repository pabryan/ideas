Gauss maps and Continuum Mechanics
====

- cont. mech. require specification of manfild + Gauss map: e.g. $\RR^n$ with the standard metric and standard Gauss map corresponding to choosing a global, parallel, orthonormal frame. This gives invariance under Gallilean transformation.
- By performing the construction in Husemoller Fibre Bundles, 5.5 Theorem and by requiring the local trivialisations to consist of a local orthonormal frame, we can construct a Riemannian Gauss map. i.e. a Gauss map $F: TM^n \to \RR^N$ with $\ip{F(X)}{F(Y)} = g(X,Y)$ where the left hand side is standard Euclidean inner product. This should be our Gauss map.

# Questions

- Given a Gauss map, one can define intergrals component-wise of vector fields and so make sense of balance of momentum in the integral sense. If one does this, is the corresponding differential version geometrically invariant?
- 3-manifolds with Killing forms. Marsden and Benn-Tucker have tried to look at conservation laws by postulating the existince of global Killing one-forms. I think this means the metric dual vector fields are Killing. Then, if I use this as a global Gauss-map (need it be Riemanian?), then do I recover their results?
- Alternatively, one could ask for invariance under Gallilean transformation. But what does this mean on a manifold? Could it be formulated in terms of frames (Grassmanians?). Or could we define this invariance to be simply invariance under the Gauss map?
- The formulation attempting to define a local momentum tensor as $P = U \tensor \density \measure$ and then considering the derivative $\lie_U P$ does not correspond to the material derivative/balance of momentum in Euclidean space. In fact, it is precisely obtained from taking this Lie derivative, but pretending that the global frame $\{E_i\}$ in invariant under $\lie_U$! That is, writing everthing w.r.t. to this frame, the material derivative is defined by taking $\lie_U$ of each component of $U \tensor \density$ thought of as an $n$-form with values in the tangent bundle. How does this work in a Riemannian manifold? This should correspond exactly to integrating the components of $U$ w.r.t. $\density \measure$ and differentiating the result.
