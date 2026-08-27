# Do Tendons Matter? Controllability of a Soft-PVTOL with Passive Elastic Arms

Supplementary material for the IEEE Robotics and Automation Letters paper
*"Do Tendons Matter? Controllability of a Soft-PVTOL with Passive Elastic Arms"*
by Gerardo Flores, Rodolfo Verdín, and Mark W. Spong.

RAPTOR Lab, Texas A&M International University · Centro de Investigaciones en
Óptica · University of Texas at Dallas

---

## What this is

The Soft-PVTOL is a planar aerial vehicle whose rigid arms are replaced by soft
continuum members. In its nominal design, tendons actively set the curvature of
each arm, giving four inputs for five degrees of freedom. This paper asks
whether the tendons are necessary at all: with them inactive, the vehicle keeps
only its two propeller thrusts and simultaneously gains unactuated elastic
dynamics.

The answer is that local controllability at hover is preserved. The enabling
mechanism is the thrust-induced bending torque `T_i · l_i · sinc(q_i)`, the only
path from the thrusts to the otherwise unactuated arm curvatures. Tendon-free
operation is therefore a viable fallback, at the cost of reduced control
authority rather than a loss of stability.

## Contents

```
media/      Supplementary videos and simulation animation
paper/      Accepted version of the manuscript (see licensing below)
```

### Videos

| File | What it shows |
|---|---|
| `soft_pvtol_teststand.*` | Test-stand validation of the passive-arm Soft-PVTOL: pitch tracking via differential thrust with tendons disabled, and passive convergence of the arm curvatures. This is the experiment reported in Section V of the paper. |
| `quadsoft_freeflight.*` | Free flight of the QuadSoft, a three-dimensional soft-arm quadrotor, with deactivated tendons, including an in-flight tendon-deactivation test. |
| `simulation_animation.*` | Takeoff-and-hover simulation of the passive-arm Soft-PVTOL. |

**On the QuadSoft recordings.** The analysis in the paper is planar and its
scope is the Soft-PVTOL. The QuadSoft free-flight videos are qualitative
evidence that tendon-free operation is physically realizable on a flying
platform; they are not a validation of the planar result. Section V-B of the
paper discusses what the planar reduction leaves out, including yaw torques
from lateral bending, aerodynamic drag on the deformed arms, and residual
thrust misalignment.

## Citation

```bibtex
@article{Flores2026Tendons,
  author  = {Flores, Gerardo and Verd\'{i}n, Rodolfo and Spong, Mark W.},
  title   = {Do Tendons Matter? {C}ontrollability of a {S}oft-{PVTOL}
             with Passive Elastic Arms},
  journal = {IEEE Robotics and Automation Letters},
  year    = {2026},
  note    = {To appear},
}
```

Update `volume`, `number`, `pages`, and `doi` once the paper appears on Xplore.

## Related work

- G. Flores and M. W. Spong, "The Soft-PVTOL: Modeling and control,"
  *Robotics and Autonomous Systems*, vol. 187, p. 104925, 2025.
- R. I. Verdín Monzón, H. A. Moreno Jiménez, M. W. Spong, and G. Flores,
  "The QuadSoft: Design, construction, and experimental validation of a soft
  and actuated quadrotor," *Proc. IEEE Int. Conf. Robot. Autom. (ICRA)*, 2026.

## Licensing

Three different terms apply, so read this before reusing anything.

**Code** — MIT License (see `LICENSE`).

**Videos and animations** — Creative Commons Attribution 4.0 International
(CC BY 4.0). Attribute to the authors and cite the paper.

**Manuscript** — The version in `paper/` is the accepted manuscript, not the
published version. Copyright is held by IEEE. It is posted here under IEEE's
author posting policy and is **not** covered by either license above. See
`paper/COPYRIGHT.txt` for the required notice.

## Contact

Gerardo Flores — gerardo.flores@tamiu.edu — RAPTOR Lab, TAMIU
