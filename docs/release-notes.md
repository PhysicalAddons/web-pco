### 0.2.0-alpha <small>- released 24.11.2022</small>

<!-- [![Release 1.1.0 banner](img/releases/pco1.6.0.jpg)](img/releases/pcoa0.1.0.jpg) -->

!!! warning ""
    We are still tackling the issue where a planet is not appearing due to uninitialized drivers. We have added the "Reinitialize drivers" button that after a parameter change will reinitialize drivers.

`new:`{: .label-new }

- Ability to add the **rings** to the planet.
- User Interface for the rings.
- Added material texture color space settings directly in the user interface for convenience.
- Rearranged UI blocks in a more intuitive fashion and also to maintain consistency between add-ons.


`improvements:`{: .label-improvements }

- Optimized PSA integration.
- Sun angular diameter now affects all lighting calculations. 
- Completely rewritten the way how nodes are generated.
- Clean up node groups to improve general performance.
- Nodes are now organized in a way to improve readability.

`fixed:`{: .label-fixed }

- Fixed wrong blending of planet depth.
- Fixed cases when some of the drivers were not linked.

!!! info "Having errors when updating add-on?"
    1. Remove previous add-on version
    2. Restart blender
    3. Install new add-on version
