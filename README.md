# tfwr
**solutions for the game 'the farmer was replaced' at v.17,feb,2026**

### readme
*whats is available*

### fn_
*functions, helpers, libraries*

### prgm_
*programs*

### ldr_
*leaderboard run*

```
function_goto (nowrarp)
reaches a cell, never wrapping the field
import: fn_goto
usage: fn_goto.do()

function_wgoto2 (wrap)
reaches a cell in the shortest amount of movements (wrapping)
import: fn_wgoto2
usage: fn_wgoto2.do(x,y)

function_single_spawn
spawns a row of drones from the main unit
import: fn_ss
usage: fn_ss.h() (horizontal)
       fn_ss.v() (vertical)

function_multi_spawn
spawns a row of drones from two different drones in opposite directions
import: fn_ms
usage: fn_ms.h() (horizontal)
       fn_ms.v() (vertical)

function_till_decide
rotates the ground bit (tilled, not tilled)
import: fn_td
usage: fn_td.do()
```
