# global_vars

## Fields:

| Name | Type | Description |
| :--- | :--- | :--- |
| realtime | float | Absolute Time |
| framecount | int | Absolute frame counter - continues to increase even if game is paused |
| absoluteframetime | float | Non-paused frametime |
| curtime | float | Current time |
| frametime | float | Time spent on last server or client frame |
| max_clients | int | Current maxplayers setting |
| tickcount | int | Simluation ticks - doesn't increase when game is paused |
| interval_per_tick | float | Simulation tick interval. tickrate = 1/interval_per_tick |
| interpolation_amount | float | Interpolation amount based on fraction of next tick |
