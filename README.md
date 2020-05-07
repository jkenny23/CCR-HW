# CCR v2.5su
Board/schematic/gerber files for the CCR project - v2.5su variant

This variant is the latest (as of 5/6/20) cost optimized version, which supports regen automatically, with use of external buffer pack (clamp circuit limits voltage at input of tester to 12.5V). All specs are the same as v2.4 otherwise (6A charge/discharge symmetric, thermally limited to 21W max without buffer pack). Fixed 2 errors in the v2.4su version, moving TL431 supply to 12V instead of 5V (delay in powering reference caused clamp circuit to engage shorting power supply if USB power was not provided first), and adding diode to 5V SMPS (MP2359 is a non-synchronous buck whereas v2.4 JW5052C was).

Details here: http://rev0.net/index.php?title=CCR
