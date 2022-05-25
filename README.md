## Exec Comparison

Comparison of several different Roblox Executors

### Environment

Performance of each Scripting Environment, aswell as the features it contains

| Name                                     | [SimpleBench](https://github.com/AstolfoBrew/SimpleBench) Score | Function Count                                               | UNC          |
| ---------------------------------------- | --------------------------------------------------------------- | ------------------------------------------------------------ | ------------ |
| [Script-Ware](https://script-ware.com/w) | [708.9573803463508](#sw-score)                                  | [180+](https://docs.script-ware.com/script-execution-engine) | ✅ (full)    |
| [Fluxus](https://fluxteam.xyz/)          | [636.4562053459221](#flux-score)                                | No Documentation (not counting env manually lol)             | ✅ (partial) |
| Synapse (too overated to get linked)     | [266.2899230358634](#syn-score)                                 | <135 (manually counted in docs)                              | ❌           |

#### SimpleBench Score Links

##### SW Score

[708.9573803463508](https://github.com/AstolfoBrew/SimpleBench/blob/1adb3d0025cc985830f20df80425d8538d94d933/out/Roblox/Script-Ware/Yielding_LT2_25-05-2022_13-55.log#L4)

##### Flux Score

[636.4562053459221](https://github.com/AstolfoBrew/SimpleBench/blob/1adb3d0025cc985830f20df80425d8538d94d933/out/Roblox/Fluxus/Yielding_LT2_25-05-2022_14-26.log#L4)

##### Syn Score

[266.2899230358634](https://github.com/AstolfoBrew/SimpleBench/blob/1adb3d0025cc985830f20df80425d8538d94d933/out/Roblox/Synapse%20v2/Yielding_LT2_25-05-2022_14-20.log#L4)

### Stability

During my time exploiting, here's how often each of the Executors crashed on me. Please note that I have used Script-Ware the most out of all of these, Synapse the 2nd most (despite buying it before buying sw), and Fluxus the least (due to me obtaining fluxus very recently)

| Executor                                 | Crash Count - Total (In Regular Conditions)\* |
| ---------------------------------------- | --------------------------------------------- |
| [Script-Ware](https://script-ware.com/w) | 12 (5)                                        |
| [Fluxus](https://fluxteam.xyz/)          | 6 (5)                                         |
| Synapse                                  | >57 (>43)                                     |

\* Regular Conditions = Crashes during Regular Execution (ie due to bugs in the scripting env) - Total = Every crash, including stress tests etc...<br/>
\*\* These exclude things such as crashes due to game client modification (ie Reshade) when provably caused by other factors.

### Launch & Attach Time

I lost the benchmarks I did between SW and Synapse on Attach & Launch time, but for every one of them, sw won by a long shot, excluding the occasional fluke.

### Update Timing

| Executor                                 | Time (in hours; on average for regular rbx updates)      |
| ---------------------------------------- | -------------------------------------------------------- |
| [Script-Ware](https://script-ware.com/w) | <2 (almost always; sometimes a tiny bit more)            |
| [Fluxus](https://fluxteam.xyz/)          | >12 (in my experience)                                   |
| Synapse                                  | ~12 (unless you're really lucky, it's gonna be aprox 12) |
