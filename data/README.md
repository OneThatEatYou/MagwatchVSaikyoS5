# Data schema
|                  | Description                                                                                                     | Type      |
|------------------|-----------------------------------------------------------------------------------------------------------------|-----------|
| Day              | Scrim day number. Day 7 represents the tournament day.                                                          | `int`     |
| Game             | Game number of the day                                                                                          | `int`     |
| Round            | Ring round in a game                                                                                            | `int`     |
| Ring Closing     | `True` if ring is closing, `False` otherwise                                                                    | `boolean` |
| Time Remaining   | Time left for the current ring state (i.e. timer below the minimap)                                             | `int`     |
| Time Stamp Value | Timestamp value (in seconds) in the VOD when the drill shot                                                     | `int`     |
| Match Elapsed    | Number of seconds since the game has started. Calculated from the time stamp value and the game start timestamp | `int`     |
| Hit              | `True` if the drill hit at least 1 target, `False` otherwise                                                    | `boolean` |
| Target           | Name of the target that is hit                                                                                  | `string`  |
| Target Team      | Team name of the target that is hit                                                                             | `string`  |