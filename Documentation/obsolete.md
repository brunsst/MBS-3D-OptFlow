### Obsolete Flags

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;flag&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp; default &nbsp; | &nbsp; explanation &nbsp; |
|------|---------|-------------|
| **--rewarp** | false | (*discontinued*) Sets rewarp to *true*. When rewarp is activated the warped version of Frame 1 is updated at the outer iteration level with the latest solution of the inner iteration scheme.  When kept *false* an unwarped copy of Frame 1 is kept in GPU memory which is warped to the current solution and passed to the inner iteration scheme. The latter is more robust and memory not pristine enough to recommend activation. |
| **--warp_mask** | false | |
