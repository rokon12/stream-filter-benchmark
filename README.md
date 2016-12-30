# stream-filter-benchmark


rokonoid@rokonoid:~/projects/java/stream-filter-benchmark$ java -jar target/benchmarks.jar 
# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: 20 iterations, 1 s each
# Measurement: 20 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: com.bazlur.MyBenchmark.testStreamWithMultipleFilter

# Run progress: 0.00% complete, ETA 00:40:00
# Fork: 1 of 10
# Warmup Iteration   1: 22510.333 ops/s
# Warmup Iteration   2: 23941.925 ops/s
# Warmup Iteration   3: 24245.650 ops/s
# Warmup Iteration   4: 24067.272 ops/s
# Warmup Iteration   5: 24294.079 ops/s
# Warmup Iteration   6: 24401.747 ops/s
# Warmup Iteration   7: 24432.286 ops/s
# Warmup Iteration   8: 24400.829 ops/s
# Warmup Iteration   9: 24350.666 ops/s
# Warmup Iteration  10: 24231.370 ops/s
# Warmup Iteration  11: 24313.790 ops/s
# Warmup Iteration  12: 24057.226 ops/s
# Warmup Iteration  13: 23680.776 ops/s
# Warmup Iteration  14: 23589.242 ops/s
# Warmup Iteration  15: 23911.082 ops/s
# Warmup Iteration  16: 23782.168 ops/s
# Warmup Iteration  17: 24033.586 ops/s
# Warmup Iteration  18: 23801.271 ops/s
# Warmup Iteration  19: 23744.451 ops/s
# Warmup Iteration  20: 24148.925 ops/s
Iteration   1: 24181.706 ops/s
Iteration   2: 23874.170 ops/s
Iteration   3: 23892.245 ops/s
Iteration   4: 24054.220 ops/s
Iteration   5: 23827.186 ops/s
Iteration   6: 23887.297 ops/s
Iteration   7: 24012.099 ops/s
Iteration   8: 23932.692 ops/s
Iteration   9: 23789.034 ops/s
Iteration  10: 23722.794 ops/s
Iteration  11: 23906.676 ops/s
Iteration  12: 23900.209 ops/s
Iteration  13: 23938.099 ops/s
Iteration  14: 23921.679 ops/s
Iteration  15: 23792.980 ops/s
Iteration  16: 23751.492 ops/s
Iteration  17: 23473.803 ops/s
Iteration  18: 23857.161 ops/s
Iteration  19: 24114.800 ops/s
Iteration  20: 24086.113 ops/s

# Run progress: 1.67% complete, ETA 00:39:36
# Fork: 2 of 10
# Warmup Iteration   1: 23251.513 ops/s
# Warmup Iteration   2: 24561.086 ops/s
# Warmup Iteration   3: 24749.802 ops/s
# Warmup Iteration   4: 24825.411 ops/s
# Warmup Iteration   5: 24790.453 ops/s
# Warmup Iteration   6: 24873.995 ops/s
# Warmup Iteration   7: 24801.857 ops/s
# Warmup Iteration   8: 24977.452 ops/s
# Warmup Iteration   9: 24884.205 ops/s
# Warmup Iteration  10: 24882.773 ops/s
# Warmup Iteration  11: 24602.940 ops/s
# Warmup Iteration  12: 24802.903 ops/s
# Warmup Iteration  13: 24760.797 ops/s
# Warmup Iteration  14: 24459.598 ops/s
# Warmup Iteration  15: 24477.865 ops/s
# Warmup Iteration  16: 24393.406 ops/s
# Warmup Iteration  17: 24605.026 ops/s
# Warmup Iteration  18: 24529.733 ops/s
# Warmup Iteration  19: 24550.165 ops/s
# Warmup Iteration  20: 24453.760 ops/s
Iteration   1: 24605.522 ops/s
Iteration   2: 24490.754 ops/s
Iteration   3: 24566.966 ops/s
Iteration   4: 24204.368 ops/s
Iteration   5: 24598.807 ops/s
Iteration   6: 24520.665 ops/s
Iteration   7: 24511.635 ops/s
Iteration   8: 24501.742 ops/s
Iteration   9: 24658.771 ops/s
Iteration  10: 24536.149 ops/s
Iteration  11: 24699.273 ops/s
Iteration  12: 24660.672 ops/s
Iteration  13: 24477.269 ops/s
Iteration  14: 24445.253 ops/s
Iteration  15: 24555.324 ops/s
Iteration  16: 24580.478 ops/s
Iteration  17: 24293.139 ops/s
Iteration  18: 24522.770 ops/s
Iteration  19: 24408.988 ops/s
Iteration  20: 24353.008 ops/s

# Run progress: 3.33% complete, ETA 00:38:54
# Fork: 3 of 10
# Warmup Iteration   1: 23364.834 ops/s
# Warmup Iteration   2: 24816.568 ops/s
# Warmup Iteration   3: 24697.996 ops/s
# Warmup Iteration   4: 24499.913 ops/s
# Warmup Iteration   5: 24648.989 ops/s
# Warmup Iteration   6: 24700.490 ops/s
# Warmup Iteration   7: 24697.495 ops/s
# Warmup Iteration   8: 24301.479 ops/s
# Warmup Iteration   9: 24463.336 ops/s
# Warmup Iteration  10: 24593.255 ops/s
# Warmup Iteration  11: 24647.475 ops/s
# Warmup Iteration  12: 24498.566 ops/s
# Warmup Iteration  13: 24737.252 ops/s
# Warmup Iteration  14: 24703.783 ops/s
# Warmup Iteration  15: 24484.480 ops/s
# Warmup Iteration  16: 24673.661 ops/s
# Warmup Iteration  17: 24639.155 ops/s
# Warmup Iteration  18: 24662.741 ops/s
# Warmup Iteration  19: 24842.017 ops/s
# Warmup Iteration  20: 24464.719 ops/s
Iteration   1: 24344.680 ops/s
Iteration   2: 24503.061 ops/s
Iteration   3: 24176.871 ops/s
Iteration   4: 24789.597 ops/s
Iteration   5: 24734.580 ops/s
Iteration   6: 24713.337 ops/s
Iteration   7: 24616.034 ops/s
Iteration   8: 24591.291 ops/s
Iteration   9: 24397.542 ops/s
Iteration  10: 24140.604 ops/s
Iteration  11: 24438.871 ops/s
Iteration  12: 24384.477 ops/s
Iteration  13: 24380.063 ops/s
Iteration  14: 24719.278 ops/s
Iteration  15: 24361.181 ops/s
Iteration  16: 24724.059 ops/s
Iteration  17: 24831.914 ops/s
Iteration  18: 24530.634 ops/s
Iteration  19: 24593.640 ops/s
Iteration  20: 24359.964 ops/s

# Run progress: 5.00% complete, ETA 00:38:13
# Fork: 4 of 10
# Warmup Iteration   1: 23147.599 ops/s
# Warmup Iteration   2: 24447.992 ops/s
# Warmup Iteration   3: 24549.979 ops/s
# Warmup Iteration   4: 24667.242 ops/s
# Warmup Iteration   5: 24695.400 ops/s
# Warmup Iteration   6: 24774.893 ops/s
# Warmup Iteration   7: 24866.753 ops/s
# Warmup Iteration   8: 24659.922 ops/s
# Warmup Iteration   9: 24707.374 ops/s
# Warmup Iteration  10: 24751.867 ops/s
# Warmup Iteration  11: 24727.280 ops/s
# Warmup Iteration  12: 24753.665 ops/s
# Warmup Iteration  13: 24540.508 ops/s
# Warmup Iteration  14: 24591.239 ops/s
# Warmup Iteration  15: 24384.110 ops/s
# Warmup Iteration  16: 24202.299 ops/s
# Warmup Iteration  17: 24503.289 ops/s
# Warmup Iteration  18: 24460.823 ops/s
# Warmup Iteration  19: 24373.735 ops/s
# Warmup Iteration  20: 24423.099 ops/s
Iteration   1: 24413.882 ops/s
Iteration   2: 24386.422 ops/s
Iteration   3: 24165.866 ops/s
Iteration   4: 24562.708 ops/s
Iteration   5: 24629.943 ops/s
Iteration   6: 24501.358 ops/s
Iteration   7: 24535.316 ops/s
Iteration   8: 24492.872 ops/s
Iteration   9: 24408.240 ops/s
Iteration  10: 24444.627 ops/s
Iteration  11: 24729.992 ops/s
Iteration  12: 24425.078 ops/s
Iteration  13: 24478.791 ops/s
Iteration  14: 24436.851 ops/s
Iteration  15: 24588.470 ops/s
Iteration  16: 24500.840 ops/s
Iteration  17: 24479.668 ops/s
Iteration  18: 24354.576 ops/s
Iteration  19: 24389.852 ops/s
Iteration  20: 24186.703 ops/s

# Run progress: 6.67% complete, ETA 00:37:33
# Fork: 5 of 10
# Warmup Iteration   1: 23380.197 ops/s
# Warmup Iteration   2: 24589.816 ops/s
# Warmup Iteration   3: 24828.012 ops/s
# Warmup Iteration   4: 24779.236 ops/s
# Warmup Iteration   5: 24686.103 ops/s
# Warmup Iteration   6: 24905.765 ops/s
# Warmup Iteration   7: 24901.917 ops/s
# Warmup Iteration   8: 24856.312 ops/s
# Warmup Iteration   9: 24817.057 ops/s
# Warmup Iteration  10: 24808.416 ops/s
# Warmup Iteration  11: 24856.197 ops/s
# Warmup Iteration  12: 24911.000 ops/s
# Warmup Iteration  13: 24759.187 ops/s
# Warmup Iteration  14: 24550.163 ops/s
# Warmup Iteration  15: 24370.923 ops/s
# Warmup Iteration  16: 24602.974 ops/s
# Warmup Iteration  17: 24205.308 ops/s
# Warmup Iteration  18: 23749.803 ops/s
# Warmup Iteration  19: 23875.841 ops/s
# Warmup Iteration  20: 24195.806 ops/s
Iteration   1: 24207.578 ops/s
Iteration   2: 24311.372 ops/s
Iteration   3: 23279.737 ops/s
Iteration   4: 24035.375 ops/s
Iteration   5: 23186.283 ops/s
Iteration   6: 23210.929 ops/s
Iteration   7: 23166.089 ops/s
Iteration   8: 23720.973 ops/s
Iteration   9: 24535.281 ops/s
Iteration  10: 24406.458 ops/s
Iteration  11: 24661.130 ops/s
Iteration  12: 24700.643 ops/s
Iteration  13: 24581.523 ops/s
Iteration  14: 24501.570 ops/s
Iteration  15: 24736.550 ops/s
Iteration  16: 24700.220 ops/s
Iteration  17: 24634.661 ops/s
Iteration  18: 24292.034 ops/s
Iteration  19: 23273.687 ops/s
Iteration  20: 23374.546 ops/s

# Run progress: 8.33% complete, ETA 00:36:53
# Fork: 6 of 10
# Warmup Iteration   1: 21826.546 ops/s
# Warmup Iteration   2: 23286.688 ops/s
# Warmup Iteration   3: 23568.398 ops/s
# Warmup Iteration   4: 23791.527 ops/s
# Warmup Iteration   5: 23495.554 ops/s
# Warmup Iteration   6: 23483.341 ops/s
# Warmup Iteration   7: 23659.896 ops/s
# Warmup Iteration   8: 24358.088 ops/s
# Warmup Iteration   9: 24733.848 ops/s
# Warmup Iteration  10: 24771.974 ops/s
# Warmup Iteration  11: 24169.159 ops/s
# Warmup Iteration  12: 23244.500 ops/s
# Warmup Iteration  13: 23509.634 ops/s
# Warmup Iteration  14: 23602.741 ops/s
# Warmup Iteration  15: 23925.594 ops/s
# Warmup Iteration  16: 25022.494 ops/s
# Warmup Iteration  17: 24659.229 ops/s
# Warmup Iteration  18: 24530.017 ops/s
# Warmup Iteration  19: 25588.702 ops/s
# Warmup Iteration  20: 23826.928 ops/s
Iteration   1: 24018.067 ops/s
Iteration   2: 24498.972 ops/s
Iteration   3: 24071.264 ops/s
Iteration   4: 23741.296 ops/s
Iteration   5: 24106.564 ops/s
Iteration   6: 23585.001 ops/s
Iteration   7: 25060.060 ops/s
Iteration   8: 25431.592 ops/s
Iteration   9: 25490.878 ops/s
Iteration  10: 24381.220 ops/s
Iteration  11: 24054.771 ops/s
Iteration  12: 24141.414 ops/s
Iteration  13: 23639.191 ops/s
Iteration  14: 24530.314 ops/s
Iteration  15: 24131.985 ops/s
Iteration  16: 24038.816 ops/s
Iteration  17: 24202.221 ops/s
Iteration  18: 22446.627 ops/s
Iteration  19: 23607.783 ops/s
Iteration  20: 23802.702 ops/s

# Run progress: 10.00% complete, ETA 00:36:13
# Fork: 7 of 10
# Warmup Iteration   1: 21921.292 ops/s
# Warmup Iteration   2: 23522.914 ops/s
# Warmup Iteration   3: 23987.966 ops/s
# Warmup Iteration   4: 24585.151 ops/s
# Warmup Iteration   5: 25051.559 ops/s
# Warmup Iteration   6: 24386.170 ops/s
# Warmup Iteration   7: 24826.389 ops/s
# Warmup Iteration   8: 25518.214 ops/s
# Warmup Iteration   9: 24626.143 ops/s
# Warmup Iteration  10: 24126.418 ops/s
# Warmup Iteration  11: 24127.490 ops/s
# Warmup Iteration  12: 23742.993 ops/s
# Warmup Iteration  13: 23732.452 ops/s
# Warmup Iteration  14: 23552.865 ops/s
# Warmup Iteration  15: 24280.008 ops/s
# Warmup Iteration  16: 23868.155 ops/s
# Warmup Iteration  17: 23284.410 ops/s
# Warmup Iteration  18: 24179.461 ops/s
# Warmup Iteration  19: 24459.050 ops/s
# Warmup Iteration  20: 24243.740 ops/s
Iteration   1: 24296.604 ops/s
Iteration   2: 24866.891 ops/s
Iteration   3: 25210.921 ops/s
Iteration   4: 23815.133 ops/s
Iteration   5: 23966.728 ops/s
Iteration   6: 24329.017 ops/s
Iteration   7: 24899.436 ops/s
Iteration   8: 24924.905 ops/s
Iteration   9: 25420.120 ops/s
Iteration  10: 24972.695 ops/s
Iteration  11: 25342.941 ops/s
Iteration  12: 25449.568 ops/s
Iteration  13: 24926.006 ops/s
Iteration  14: 24129.824 ops/s
Iteration  15: 24437.889 ops/s
Iteration  16: 25131.495 ops/s
Iteration  17: 25565.342 ops/s
Iteration  18: 25725.575 ops/s
Iteration  19: 25063.231 ops/s
Iteration  20: 24327.993 ops/s

# Run progress: 11.67% complete, ETA 00:35:33
# Fork: 8 of 10
# Warmup Iteration   1: 23722.711 ops/s
# Warmup Iteration   2: 24031.956 ops/s
# Warmup Iteration   3: 24777.887 ops/s
# Warmup Iteration   4: 24179.901 ops/s
# Warmup Iteration   5: 25187.699 ops/s
# Warmup Iteration   6: 24309.267 ops/s
# Warmup Iteration   7: 25449.759 ops/s
# Warmup Iteration   8: 24881.109 ops/s
# Warmup Iteration   9: 24096.167 ops/s
# Warmup Iteration  10: 22491.329 ops/s
# Warmup Iteration  11: 23756.288 ops/s
# Warmup Iteration  12: 23522.144 ops/s
# Warmup Iteration  13: 22288.792 ops/s
# Warmup Iteration  14: 22060.667 ops/s
# Warmup Iteration  15: 22825.538 ops/s
# Warmup Iteration  16: 24251.844 ops/s
# Warmup Iteration  17: 23336.539 ops/s
# Warmup Iteration  18: 22976.265 ops/s
# Warmup Iteration  19: 21998.894 ops/s
# Warmup Iteration  20: 21419.074 ops/s
Iteration   1: 21932.334 ops/s
Iteration   2: 22679.488 ops/s
Iteration   3: 21655.869 ops/s
Iteration   4: 22128.474 ops/s
Iteration   5: 22960.147 ops/s
Iteration   6: 23338.199 ops/s
Iteration   7: 23428.023 ops/s
Iteration   8: 23651.742 ops/s
Iteration   9: 24321.253 ops/s
Iteration  10: 23157.879 ops/s
Iteration  11: 23504.861 ops/s
Iteration  12: 22943.335 ops/s
Iteration  13: 22403.456 ops/s
Iteration  14: 22792.915 ops/s
Iteration  15: 21802.427 ops/s
Iteration  16: 24387.737 ops/s
Iteration  17: 23254.073 ops/s
Iteration  18: 23354.904 ops/s
Iteration  19: 23711.664 ops/s
Iteration  20: 24334.143 ops/s

# Run progress: 13.33% complete, ETA 00:34:52
# Fork: 9 of 10
# Warmup Iteration   1: 22789.225 ops/s
# Warmup Iteration   2: 24952.110 ops/s
# Warmup Iteration   3: 24758.477 ops/s
# Warmup Iteration   4: 23806.846 ops/s
# Warmup Iteration   5: 24742.222 ops/s
# Warmup Iteration   6: 25360.027 ops/s
# Warmup Iteration   7: 24596.091 ops/s
# Warmup Iteration   8: 22922.962 ops/s
# Warmup Iteration   9: 22021.923 ops/s
# Warmup Iteration  10: 22800.370 ops/s
# Warmup Iteration  11: 25021.483 ops/s
# Warmup Iteration  12: 24540.490 ops/s
# Warmup Iteration  13: 24809.529 ops/s
# Warmup Iteration  14: 25093.343 ops/s
# Warmup Iteration  15: 25066.469 ops/s
# Warmup Iteration  16: 24670.207 ops/s
# Warmup Iteration  17: 25165.308 ops/s
# Warmup Iteration  18: 25136.825 ops/s
# Warmup Iteration  19: 25012.500 ops/s
# Warmup Iteration  20: 24854.183 ops/s
Iteration   1: 24941.236 ops/s
Iteration   2: 25082.790 ops/s
Iteration   3: 25123.594 ops/s
Iteration   4: 24980.311 ops/s
Iteration   5: 25034.537 ops/s
Iteration   6: 25207.132 ops/s
Iteration   7: 24954.761 ops/s
Iteration   8: 25042.530 ops/s
Iteration   9: 24986.895 ops/s
Iteration  10: 24985.863 ops/s
Iteration  11: 25149.623 ops/s
Iteration  12: 25015.266 ops/s
Iteration  13: 25037.976 ops/s
Iteration  14: 25109.556 ops/s
Iteration  15: 25178.221 ops/s
Iteration  16: 24898.561 ops/s
Iteration  17: 24985.542 ops/s
Iteration  18: 25254.700 ops/s
Iteration  19: 24503.196 ops/s
Iteration  20: 24914.075 ops/s

# Run progress: 15.00% complete, ETA 00:34:12
# Fork: 10 of 10
# Warmup Iteration   1: 23510.748 ops/s
# Warmup Iteration   2: 24180.340 ops/s
# Warmup Iteration   3: 25239.531 ops/s
# Warmup Iteration   4: 25031.863 ops/s
# Warmup Iteration   5: 24964.303 ops/s
# Warmup Iteration   6: 25053.535 ops/s
# Warmup Iteration   7: 25269.452 ops/s
# Warmup Iteration   8: 24999.421 ops/s
# Warmup Iteration   9: 25258.849 ops/s
# Warmup Iteration  10: 25273.544 ops/s
# Warmup Iteration  11: 25593.624 ops/s
# Warmup Iteration  12: 25362.613 ops/s
# Warmup Iteration  13: 25379.492 ops/s
# Warmup Iteration  14: 24827.289 ops/s
# Warmup Iteration  15: 25309.315 ops/s
# Warmup Iteration  16: 25290.642 ops/s
# Warmup Iteration  17: 25234.333 ops/s
# Warmup Iteration  18: 25236.454 ops/s
# Warmup Iteration  19: 24964.029 ops/s
# Warmup Iteration  20: 25226.887 ops/s
Iteration   1: 24693.763 ops/s
Iteration   2: 24847.400 ops/s
Iteration   3: 25207.778 ops/s
Iteration   4: 25296.294 ops/s
Iteration   5: 25268.440 ops/s
Iteration   6: 25296.642 ops/s
Iteration   7: 25226.625 ops/s
Iteration   8: 25108.221 ops/s
Iteration   9: 25198.795 ops/s
Iteration  10: 25275.102 ops/s
Iteration  11: 24689.659 ops/s
Iteration  12: 25086.958 ops/s
Iteration  13: 25064.169 ops/s
Iteration  14: 25133.683 ops/s
Iteration  15: 25234.393 ops/s
Iteration  16: 24766.739 ops/s
Iteration  17: 24981.006 ops/s
Iteration  18: 25521.295 ops/s
Iteration  19: 25363.162 ops/s
Iteration  20: 25162.304 ops/s


Result "testStreamWithMultipleFilter":
  24367.016 ±(99.9%) 169.686 ops/s [Average]
  (min, avg, max) = (21655.869, 24367.016, 25725.575), stdev = 718.460
  CI (99.9%): [24197.330, 24536.701] (assumes normal distribution)


# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: 20 iterations, 1 s each
# Measurement: 20 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: com.bazlur.MyBenchmark.testStreamWithSingleFilter

# Run progress: 16.67% complete, ETA 00:33:32
# Fork: 1 of 10
# Warmup Iteration   1: 30699.382 ops/s
# Warmup Iteration   2: 32004.271 ops/s
# Warmup Iteration   3: 32309.401 ops/s
# Warmup Iteration   4: 32036.017 ops/s
# Warmup Iteration   5: 32811.209 ops/s
# Warmup Iteration   6: 32723.569 ops/s
# Warmup Iteration   7: 32594.095 ops/s
# Warmup Iteration   8: 32738.483 ops/s
# Warmup Iteration   9: 32653.913 ops/s
# Warmup Iteration  10: 32465.995 ops/s
# Warmup Iteration  11: 32301.769 ops/s
# Warmup Iteration  12: 32431.713 ops/s
# Warmup Iteration  13: 32421.543 ops/s
# Warmup Iteration  14: 32238.346 ops/s
# Warmup Iteration  15: 32373.676 ops/s
# Warmup Iteration  16: 32394.253 ops/s
# Warmup Iteration  17: 32322.038 ops/s
# Warmup Iteration  18: 31960.401 ops/s
# Warmup Iteration  19: 32312.438 ops/s
# Warmup Iteration  20: 32639.980 ops/s
Iteration   1: 32624.686 ops/s
Iteration   2: 32546.571 ops/s
Iteration   3: 31895.605 ops/s
Iteration   4: 32284.392 ops/s
Iteration   5: 32436.349 ops/s
Iteration   6: 32364.909 ops/s
Iteration   7: 32242.201 ops/s
Iteration   8: 32138.813 ops/s
Iteration   9: 32182.715 ops/s
Iteration  10: 32718.665 ops/s
Iteration  11: 32391.031 ops/s
Iteration  12: 32447.717 ops/s
Iteration  13: 32229.242 ops/s
Iteration  14: 32594.738 ops/s
Iteration  15: 32296.319 ops/s
Iteration  16: 32260.089 ops/s
Iteration  17: 32397.657 ops/s
Iteration  18: 32347.636 ops/s
Iteration  19: 32262.523 ops/s
Iteration  20: 32654.727 ops/s

# Run progress: 18.33% complete, ETA 00:32:52
# Fork: 2 of 10
# Warmup Iteration   1: 30706.123 ops/s
# Warmup Iteration   2: 32326.318 ops/s
# Warmup Iteration   3: 32046.864 ops/s
# Warmup Iteration   4: 32549.236 ops/s
# Warmup Iteration   5: 32773.534 ops/s
# Warmup Iteration   6: 32691.810 ops/s
# Warmup Iteration   7: 32623.872 ops/s
# Warmup Iteration   8: 32230.154 ops/s
# Warmup Iteration   9: 32699.686 ops/s
# Warmup Iteration  10: 32764.149 ops/s
# Warmup Iteration  11: 32371.038 ops/s
# Warmup Iteration  12: 32103.190 ops/s
# Warmup Iteration  13: 32834.273 ops/s
# Warmup Iteration  14: 32634.396 ops/s
# Warmup Iteration  15: 32532.386 ops/s
# Warmup Iteration  16: 32476.203 ops/s
# Warmup Iteration  17: 32570.131 ops/s
# Warmup Iteration  18: 32195.510 ops/s
# Warmup Iteration  19: 32349.241 ops/s
# Warmup Iteration  20: 32414.551 ops/s
Iteration   1: 32531.645 ops/s
Iteration   2: 32564.608 ops/s
Iteration   3: 32566.982 ops/s
Iteration   4: 32395.150 ops/s
Iteration   5: 32038.735 ops/s
Iteration   6: 32517.346 ops/s
Iteration   7: 33188.610 ops/s
Iteration   8: 32997.613 ops/s
Iteration   9: 32792.905 ops/s
Iteration  10: 32841.047 ops/s
Iteration  11: 32695.033 ops/s
Iteration  12: 32400.669 ops/s
Iteration  13: 32517.752 ops/s
Iteration  14: 32680.554 ops/s
Iteration  15: 32545.361 ops/s
Iteration  16: 32602.522 ops/s
Iteration  17: 32790.720 ops/s
Iteration  18: 32572.112 ops/s
Iteration  19: 32617.741 ops/s
Iteration  20: 32766.017 ops/s

# Run progress: 20.00% complete, ETA 00:32:11
# Fork: 3 of 10
# Warmup Iteration   1: 30716.730 ops/s
# Warmup Iteration   2: 32386.900 ops/s
# Warmup Iteration   3: 32610.357 ops/s
# Warmup Iteration   4: 32262.874 ops/s
# Warmup Iteration   5: 32549.242 ops/s
# Warmup Iteration   6: 32739.406 ops/s
# Warmup Iteration   7: 32187.721 ops/s
# Warmup Iteration   8: 32573.609 ops/s
# Warmup Iteration   9: 32288.225 ops/s
# Warmup Iteration  10: 32440.631 ops/s
# Warmup Iteration  11: 32554.237 ops/s
# Warmup Iteration  12: 31990.413 ops/s
# Warmup Iteration  13: 32423.919 ops/s
# Warmup Iteration  14: 32273.325 ops/s
# Warmup Iteration  15: 32621.217 ops/s
# Warmup Iteration  16: 32677.772 ops/s
# Warmup Iteration  17: 32383.714 ops/s
# Warmup Iteration  18: 32329.246 ops/s
# Warmup Iteration  19: 32075.713 ops/s
# Warmup Iteration  20: 32474.310 ops/s
Iteration   1: 32089.607 ops/s
Iteration   2: 32363.404 ops/s
Iteration   3: 32200.461 ops/s
Iteration   4: 32125.957 ops/s
Iteration   5: 32321.697 ops/s
Iteration   6: 32495.980 ops/s
Iteration   7: 32153.842 ops/s
Iteration   8: 32628.756 ops/s
Iteration   9: 32347.870 ops/s
Iteration  10: 32387.711 ops/s
Iteration  11: 32518.721 ops/s
Iteration  12: 32423.599 ops/s
Iteration  13: 32396.079 ops/s
Iteration  14: 32253.322 ops/s
Iteration  15: 32281.782 ops/s
Iteration  16: 32394.322 ops/s
Iteration  17: 32509.585 ops/s
Iteration  18: 32503.206 ops/s
Iteration  19: 32381.268 ops/s
Iteration  20: 32554.036 ops/s

# Run progress: 21.67% complete, ETA 00:31:31
# Fork: 4 of 10
# Warmup Iteration   1: 30468.712 ops/s
# Warmup Iteration   2: 32782.910 ops/s
# Warmup Iteration   3: 32623.371 ops/s
# Warmup Iteration   4: 33056.336 ops/s
# Warmup Iteration   5: 32739.643 ops/s
# Warmup Iteration   6: 33231.094 ops/s
# Warmup Iteration   7: 33052.632 ops/s
# Warmup Iteration   8: 32840.498 ops/s
# Warmup Iteration   9: 33342.722 ops/s
# Warmup Iteration  10: 32953.014 ops/s
# Warmup Iteration  11: 33054.529 ops/s
# Warmup Iteration  12: 33314.337 ops/s
# Warmup Iteration  13: 33299.135 ops/s
# Warmup Iteration  14: 33100.270 ops/s
# Warmup Iteration  15: 32802.047 ops/s
# Warmup Iteration  16: 32977.282 ops/s
# Warmup Iteration  17: 32853.210 ops/s
# Warmup Iteration  18: 32542.392 ops/s
# Warmup Iteration  19: 32720.682 ops/s
# Warmup Iteration  20: 32831.303 ops/s
Iteration   1: 32935.619 ops/s
Iteration   2: 32819.610 ops/s
Iteration   3: 32635.739 ops/s
Iteration   4: 32392.943 ops/s
Iteration   5: 32916.767 ops/s
Iteration   6: 32715.635 ops/s
Iteration   7: 29794.918 ops/s
Iteration   8: 31730.552 ops/s
Iteration   9: 32680.231 ops/s
Iteration  10: 32964.160 ops/s
Iteration  11: 32793.087 ops/s
Iteration  12: 32044.252 ops/s
Iteration  13: 31208.718 ops/s
Iteration  14: 30778.951 ops/s
Iteration  15: 30560.128 ops/s
Iteration  16: 30968.258 ops/s
Iteration  17: 31660.574 ops/s
Iteration  18: 32114.806 ops/s
Iteration  19: 33176.600 ops/s
Iteration  20: 33188.409 ops/s

# Run progress: 23.33% complete, ETA 00:30:51
# Fork: 5 of 10
# Warmup Iteration   1: 30773.707 ops/s
# Warmup Iteration   2: 31887.915 ops/s
# Warmup Iteration   3: 32399.911 ops/s
# Warmup Iteration   4: 32834.552 ops/s
# Warmup Iteration   5: 33014.655 ops/s
# Warmup Iteration   6: 32862.081 ops/s
# Warmup Iteration   7: 33030.404 ops/s
# Warmup Iteration   8: 32873.178 ops/s
# Warmup Iteration   9: 33226.879 ops/s
# Warmup Iteration  10: 33096.855 ops/s
# Warmup Iteration  11: 32511.359 ops/s
# Warmup Iteration  12: 32752.349 ops/s
# Warmup Iteration  13: 32874.457 ops/s
# Warmup Iteration  14: 32325.120 ops/s
# Warmup Iteration  15: 33003.448 ops/s
# Warmup Iteration  16: 33154.447 ops/s
# Warmup Iteration  17: 33091.537 ops/s
# Warmup Iteration  18: 32666.076 ops/s
# Warmup Iteration  19: 32879.785 ops/s
# Warmup Iteration  20: 33217.555 ops/s
Iteration   1: 33147.199 ops/s
Iteration   2: 32996.070 ops/s
Iteration   3: 32790.636 ops/s
Iteration   4: 32879.525 ops/s
Iteration   5: 33124.470 ops/s
Iteration   6: 32899.456 ops/s
Iteration   7: 33208.107 ops/s
Iteration   8: 33032.273 ops/s
Iteration   9: 33067.732 ops/s
Iteration  10: 33223.339 ops/s
Iteration  11: 33130.304 ops/s
Iteration  12: 32892.024 ops/s
Iteration  13: 33120.463 ops/s
Iteration  14: 32993.610 ops/s
Iteration  15: 33101.003 ops/s
Iteration  16: 32991.983 ops/s
Iteration  17: 32996.720 ops/s
Iteration  18: 33322.643 ops/s
Iteration  19: 33292.164 ops/s
Iteration  20: 33153.975 ops/s

# Run progress: 25.00% complete, ETA 00:30:10
# Fork: 6 of 10
# Warmup Iteration   1: 30774.465 ops/s
# Warmup Iteration   2: 32565.535 ops/s
# Warmup Iteration   3: 32802.062 ops/s
# Warmup Iteration   4: 32330.049 ops/s
# Warmup Iteration   5: 33223.288 ops/s
# Warmup Iteration   6: 32958.777 ops/s
# Warmup Iteration   7: 33154.919 ops/s
# Warmup Iteration   8: 33309.695 ops/s
# Warmup Iteration   9: 32987.158 ops/s
# Warmup Iteration  10: 32469.513 ops/s
# Warmup Iteration  11: 32868.962 ops/s
# Warmup Iteration  12: 32784.062 ops/s
# Warmup Iteration  13: 32825.128 ops/s
# Warmup Iteration  14: 33032.706 ops/s
# Warmup Iteration  15: 32753.160 ops/s
# Warmup Iteration  16: 32657.064 ops/s
# Warmup Iteration  17: 33003.780 ops/s
# Warmup Iteration  18: 32878.367 ops/s
# Warmup Iteration  19: 32759.478 ops/s
# Warmup Iteration  20: 32776.273 ops/s
Iteration   1: 32788.319 ops/s
Iteration   2: 32790.652 ops/s
Iteration   3: 32939.685 ops/s
Iteration   4: 32567.728 ops/s
Iteration   5: 32513.194 ops/s
Iteration   6: 32816.257 ops/s
Iteration   7: 32958.479 ops/s
Iteration   8: 32999.330 ops/s
Iteration   9: 32587.589 ops/s
Iteration  10: 32990.219 ops/s
Iteration  11: 33051.494 ops/s
Iteration  12: 32858.141 ops/s
Iteration  13: 32804.563 ops/s
Iteration  14: 32874.551 ops/s
Iteration  15: 32828.665 ops/s
Iteration  16: 32849.294 ops/s
Iteration  17: 32906.475 ops/s
Iteration  18: 32947.665 ops/s
Iteration  19: 32994.247 ops/s
Iteration  20: 32941.145 ops/s

# Run progress: 26.67% complete, ETA 00:29:30
# Fork: 7 of 10
# Warmup Iteration   1: 31851.796 ops/s
# Warmup Iteration   2: 33214.815 ops/s
# Warmup Iteration   3: 33634.992 ops/s
# Warmup Iteration   4: 33631.555 ops/s
# Warmup Iteration   5: 33819.280 ops/s
# Warmup Iteration   6: 33769.086 ops/s
# Warmup Iteration   7: 33692.682 ops/s
# Warmup Iteration   8: 33512.344 ops/s
# Warmup Iteration   9: 33431.105 ops/s
# Warmup Iteration  10: 33525.038 ops/s
# Warmup Iteration  11: 33169.533 ops/s
# Warmup Iteration  12: 33472.028 ops/s
# Warmup Iteration  13: 33189.340 ops/s
# Warmup Iteration  14: 33212.127 ops/s
# Warmup Iteration  15: 33364.758 ops/s
# Warmup Iteration  16: 33480.896 ops/s
# Warmup Iteration  17: 33231.220 ops/s
# Warmup Iteration  18: 33314.289 ops/s
# Warmup Iteration  19: 33369.004 ops/s
# Warmup Iteration  20: 33256.716 ops/s
Iteration   1: 33326.095 ops/s
Iteration   2: 33284.806 ops/s
Iteration   3: 33109.751 ops/s
Iteration   4: 33477.104 ops/s
Iteration   5: 33349.395 ops/s
Iteration   6: 33066.370 ops/s
Iteration   7: 33514.260 ops/s
Iteration   8: 33713.338 ops/s
Iteration   9: 33637.228 ops/s
Iteration  10: 33539.523 ops/s
Iteration  11: 33351.558 ops/s
Iteration  12: 33290.472 ops/s
Iteration  13: 33418.646 ops/s
Iteration  14: 33146.099 ops/s
Iteration  15: 33374.170 ops/s
Iteration  16: 33400.434 ops/s
Iteration  17: 33453.559 ops/s
Iteration  18: 33293.656 ops/s
Iteration  19: 33362.246 ops/s
Iteration  20: 33413.446 ops/s

# Run progress: 28.33% complete, ETA 00:28:50
# Fork: 8 of 10
# Warmup Iteration   1: 31932.324 ops/s
# Warmup Iteration   2: 32647.884 ops/s
# Warmup Iteration   3: 32749.304 ops/s
# Warmup Iteration   4: 33663.621 ops/s
# Warmup Iteration   5: 33377.184 ops/s
# Warmup Iteration   6: 33357.821 ops/s
# Warmup Iteration   7: 33511.045 ops/s
# Warmup Iteration   8: 33548.664 ops/s
# Warmup Iteration   9: 33510.933 ops/s
# Warmup Iteration  10: 33461.719 ops/s
# Warmup Iteration  11: 33527.404 ops/s
# Warmup Iteration  12: 33361.067 ops/s
# Warmup Iteration  13: 33386.836 ops/s
# Warmup Iteration  14: 33248.899 ops/s
# Warmup Iteration  15: 33543.903 ops/s
# Warmup Iteration  16: 33408.554 ops/s
# Warmup Iteration  17: 33159.837 ops/s
# Warmup Iteration  18: 33371.571 ops/s
# Warmup Iteration  19: 33464.790 ops/s
# Warmup Iteration  20: 33171.615 ops/s
Iteration   1: 33294.154 ops/s
Iteration   2: 33519.344 ops/s
Iteration   3: 33596.516 ops/s
Iteration   4: 33511.340 ops/s
Iteration   5: 33302.140 ops/s
Iteration   6: 33423.231 ops/s
Iteration   7: 33454.373 ops/s
Iteration   8: 33331.968 ops/s
Iteration   9: 33440.201 ops/s
Iteration  10: 33395.497 ops/s
Iteration  11: 33311.373 ops/s
Iteration  12: 33437.582 ops/s
Iteration  13: 33439.682 ops/s
Iteration  14: 33280.517 ops/s
Iteration  15: 33451.448 ops/s
Iteration  16: 33223.125 ops/s
Iteration  17: 33111.564 ops/s
Iteration  18: 33585.398 ops/s
Iteration  19: 33353.916 ops/s
Iteration  20: 33442.365 ops/s

# Run progress: 30.00% complete, ETA 00:28:09
# Fork: 9 of 10
# Warmup Iteration   1: 31529.070 ops/s
# Warmup Iteration   2: 33011.705 ops/s
# Warmup Iteration   3: 33224.591 ops/s
# Warmup Iteration   4: 33273.247 ops/s
# Warmup Iteration   5: 33378.152 ops/s
# Warmup Iteration   6: 33271.189 ops/s
# Warmup Iteration   7: 32699.987 ops/s
# Warmup Iteration   8: 33178.449 ops/s
# Warmup Iteration   9: 32080.359 ops/s
# Warmup Iteration  10: 31239.700 ops/s
# Warmup Iteration  11: 30838.569 ops/s
# Warmup Iteration  12: 32259.806 ops/s
# Warmup Iteration  13: 32716.608 ops/s
# Warmup Iteration  14: 32701.491 ops/s
# Warmup Iteration  15: 33126.747 ops/s
# Warmup Iteration  16: 32656.428 ops/s
# Warmup Iteration  17: 31798.024 ops/s
# Warmup Iteration  18: 32422.241 ops/s
# Warmup Iteration  19: 32398.457 ops/s
# Warmup Iteration  20: 33236.838 ops/s
Iteration   1: 33259.893 ops/s
Iteration   2: 33106.089 ops/s
Iteration   3: 32905.040 ops/s
Iteration   4: 33045.658 ops/s
Iteration   5: 31736.329 ops/s
Iteration   6: 33057.274 ops/s
Iteration   7: 33175.219 ops/s
Iteration   8: 33301.384 ops/s
Iteration   9: 33054.338 ops/s
Iteration  10: 33250.552 ops/s
Iteration  11: 33229.084 ops/s
Iteration  12: 33060.643 ops/s
Iteration  13: 32943.077 ops/s
Iteration  14: 32956.254 ops/s
Iteration  15: 33010.467 ops/s
Iteration  16: 32871.593 ops/s
Iteration  17: 32855.589 ops/s
Iteration  18: 32792.532 ops/s
Iteration  19: 32951.049 ops/s
Iteration  20: 32770.653 ops/s

# Run progress: 31.67% complete, ETA 00:27:29
# Fork: 10 of 10
# Warmup Iteration   1: 30964.334 ops/s
# Warmup Iteration   2: 32110.904 ops/s
# Warmup Iteration   3: 32609.007 ops/s
# Warmup Iteration   4: 32466.380 ops/s
# Warmup Iteration   5: 33021.511 ops/s
# Warmup Iteration   6: 33063.298 ops/s
# Warmup Iteration   7: 32992.544 ops/s
# Warmup Iteration   8: 32924.638 ops/s
# Warmup Iteration   9: 32834.642 ops/s
# Warmup Iteration  10: 32952.457 ops/s
# Warmup Iteration  11: 32698.311 ops/s
# Warmup Iteration  12: 32478.680 ops/s
# Warmup Iteration  13: 32730.848 ops/s
# Warmup Iteration  14: 32614.860 ops/s
# Warmup Iteration  15: 32760.596 ops/s
# Warmup Iteration  16: 32545.907 ops/s
# Warmup Iteration  17: 32753.102 ops/s
# Warmup Iteration  18: 32702.587 ops/s
# Warmup Iteration  19: 32658.627 ops/s
# Warmup Iteration  20: 32682.084 ops/s
Iteration   1: 32331.999 ops/s
Iteration   2: 32587.742 ops/s
Iteration   3: 32702.997 ops/s
Iteration   4: 32689.795 ops/s
Iteration   5: 32651.492 ops/s
Iteration   6: 32690.614 ops/s
Iteration   7: 32877.216 ops/s
Iteration   8: 32814.386 ops/s
Iteration   9: 32586.850 ops/s
Iteration  10: 32513.731 ops/s
Iteration  11: 32885.224 ops/s
Iteration  12: 32740.182 ops/s
Iteration  13: 32591.241 ops/s
Iteration  14: 32512.259 ops/s
Iteration  15: 32646.580 ops/s
Iteration  16: 32582.588 ops/s
Iteration  17: 32696.652 ops/s
Iteration  18: 32740.179 ops/s
Iteration  19: 32756.712 ops/s
Iteration  20: 32750.159 ops/s


Result "testStreamWithSingleFilter":
  32779.157 ±(99.9%) 127.938 ops/s [Average]
  (min, avg, max) = (29794.918, 32779.157, 33713.338), stdev = 541.696
  CI (99.9%): [32651.220, 32907.095] (assumes normal distribution)


# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: 20 iterations, 1 s each
# Measurement: 20 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: com.bazlur.MyBenchmark.testStreamWithMultipleFilter

# Run progress: 33.33% complete, ETA 00:26:49
# Fork: 1 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 35.00% complete, ETA 00:26:09
# Fork: 2 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 36.67% complete, ETA 00:25:28
# Fork: 3 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 38.33% complete, ETA 00:24:48
# Fork: 4 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 40.00% complete, ETA 00:24:08
# Fork: 5 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 41.67% complete, ETA 00:23:28
# Fork: 6 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 43.33% complete, ETA 00:22:47
# Fork: 7 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 45.00% complete, ETA 00:22:07
# Fork: 8 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 46.67% complete, ETA 00:21:27
# Fork: 9 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op

# Run progress: 48.33% complete, ETA 00:20:47
# Fork: 10 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
Iteration   2: ≈ 10⁻⁴ s/op
Iteration   3: ≈ 10⁻⁴ s/op
Iteration   4: ≈ 10⁻⁴ s/op
Iteration   5: ≈ 10⁻⁴ s/op
Iteration   6: ≈ 10⁻⁴ s/op
Iteration   7: ≈ 10⁻⁴ s/op
Iteration   8: ≈ 10⁻⁴ s/op
Iteration   9: ≈ 10⁻⁴ s/op
Iteration  10: ≈ 10⁻⁴ s/op
Iteration  11: ≈ 10⁻⁴ s/op
Iteration  12: ≈ 10⁻⁴ s/op
Iteration  13: ≈ 10⁻⁴ s/op
Iteration  14: ≈ 10⁻⁴ s/op
Iteration  15: ≈ 10⁻⁴ s/op
Iteration  16: ≈ 10⁻⁴ s/op
Iteration  17: ≈ 10⁻⁴ s/op
Iteration  18: ≈ 10⁻⁴ s/op
Iteration  19: ≈ 10⁻⁴ s/op
Iteration  20: ≈ 10⁻⁴ s/op


Result "testStreamWithMultipleFilter":
  ≈ 10⁻⁴ s/op


# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: 20 iterations, 1 s each
# Measurement: 20 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: com.bazlur.MyBenchmark.testStreamWithSingleFilter

# Run progress: 50.00% complete, ETA 00:20:06
# Fork: 1 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 51.67% complete, ETA 00:19:26
# Fork: 2 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 53.33% complete, ETA 00:18:46
# Fork: 3 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 55.00% complete, ETA 00:18:06
# Fork: 4 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 56.67% complete, ETA 00:17:25
# Fork: 5 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 58.33% complete, ETA 00:16:45
# Fork: 6 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 60.00% complete, ETA 00:16:05
# Fork: 7 of 10
# Warmup Iteration   1: ≈ 10⁻⁵ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 61.67% complete, ETA 00:15:25
# Fork: 8 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 63.33% complete, ETA 00:14:45
# Fork: 9 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op

# Run progress: 65.00% complete, ETA 00:14:04
# Fork: 10 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
Iteration   2: ≈ 10⁻⁵ s/op
Iteration   3: ≈ 10⁻⁵ s/op
Iteration   4: ≈ 10⁻⁵ s/op
Iteration   5: ≈ 10⁻⁵ s/op
Iteration   6: ≈ 10⁻⁵ s/op
Iteration   7: ≈ 10⁻⁵ s/op
Iteration   8: ≈ 10⁻⁵ s/op
Iteration   9: ≈ 10⁻⁵ s/op
Iteration  10: ≈ 10⁻⁵ s/op
Iteration  11: ≈ 10⁻⁵ s/op
Iteration  12: ≈ 10⁻⁵ s/op
Iteration  13: ≈ 10⁻⁵ s/op
Iteration  14: ≈ 10⁻⁵ s/op
Iteration  15: ≈ 10⁻⁵ s/op
Iteration  16: ≈ 10⁻⁵ s/op
Iteration  17: ≈ 10⁻⁵ s/op
Iteration  18: ≈ 10⁻⁵ s/op
Iteration  19: ≈ 10⁻⁵ s/op
Iteration  20: ≈ 10⁻⁵ s/op


Result "testStreamWithSingleFilter":
  ≈ 10⁻⁵ s/op


# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: 20 iterations, 1 s each
# Measurement: 20 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: com.bazlur.MyBenchmark.testStreamWithMultipleFilter

# Run progress: 66.67% complete, ETA 00:13:24
# Fork: 1 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.003 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.003 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.004 s/op
                 testStreamWithMultipleFilter·p1.00:   0.005 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op


# Run progress: 68.33% complete, ETA 00:12:44
# Fork: 2 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.003 s/op
                 testStreamWithMultipleFilter·p1.00:   0.004 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op


# Run progress: 70.00% complete, ETA 00:12:04
# Fork: 3 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.004 s/op
                 testStreamWithMultipleFilter·p1.00:   0.006 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op


# Run progress: 71.67% complete, ETA 00:11:23
# Fork: 4 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.003 s/op
                 testStreamWithMultipleFilter·p1.00:   0.004 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.003 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op


# Run progress: 73.33% complete, ETA 00:10:43
# Fork: 5 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.003 s/op
                 testStreamWithMultipleFilter·p1.00:   0.004 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.003 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op


# Run progress: 75.00% complete, ETA 00:10:03
# Fork: 6 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.003 s/op
                 testStreamWithMultipleFilter·p1.00:   0.003 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.003 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op


# Run progress: 76.67% complete, ETA 00:09:23
# Fork: 7 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op


# Run progress: 78.33% complete, ETA 00:08:43
# Fork: 8 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.003 s/op
                 testStreamWithMultipleFilter·p1.00:   0.004 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.003 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.003 s/op
                 testStreamWithMultipleFilter·p1.00:   0.004 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op


# Run progress: 80.00% complete, ETA 00:08:02
# Fork: 9 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op


# Run progress: 81.67% complete, ETA 00:07:22
# Fork: 10 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁴ s/op
# Warmup Iteration   3: ≈ 10⁻⁴ s/op
# Warmup Iteration   4: ≈ 10⁻⁴ s/op
# Warmup Iteration   5: ≈ 10⁻⁴ s/op
# Warmup Iteration   6: ≈ 10⁻⁴ s/op
# Warmup Iteration   7: ≈ 10⁻⁴ s/op
# Warmup Iteration   8: ≈ 10⁻⁴ s/op
# Warmup Iteration   9: ≈ 10⁻⁴ s/op
# Warmup Iteration  10: ≈ 10⁻⁴ s/op
# Warmup Iteration  11: ≈ 10⁻⁴ s/op
# Warmup Iteration  12: ≈ 10⁻⁴ s/op
# Warmup Iteration  13: ≈ 10⁻⁴ s/op
# Warmup Iteration  14: ≈ 10⁻⁴ s/op
# Warmup Iteration  15: ≈ 10⁻⁴ s/op
# Warmup Iteration  16: ≈ 10⁻⁴ s/op
# Warmup Iteration  17: ≈ 10⁻⁴ s/op
# Warmup Iteration  18: ≈ 10⁻⁴ s/op
# Warmup Iteration  19: ≈ 10⁻⁴ s/op
# Warmup Iteration  20: ≈ 10⁻⁴ s/op
Iteration   1: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   7: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration   9: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  12: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.002 s/op
                 testStreamWithMultipleFilter·p1.00:   0.002 s/op

Iteration  14: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.00:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.50:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.90:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithMultipleFilter·p0.999:  0.001 s/op
                 testStreamWithMultipleFilter·p0.9999: 0.001 s/op
                 testStreamWithMultipleFilter·p1.00:   0.001 s/op



Result "testStreamWithMultipleFilter":
  N = 2581418
  mean =     ≈ 10⁻⁴ ±(99.9%) 0.001 s/op

  Histogram, s/op:
    [0.000, 0.001) = 2578512 
    [0.001, 0.001) = 2798 
    [0.001, 0.002) = 57 
    [0.002, 0.002) = 22 
    [0.002, 0.003) = 15 
    [0.003, 0.003) = 5 
    [0.003, 0.004) = 2 
    [0.004, 0.004) = 4 
    [0.004, 0.005) = 1 
    [0.005, 0.005) = 0 
    [0.005, 0.006) = 1 

  Percentiles, s/op:
      p(0.0000) =     ≈ 10⁻⁴ s/op
     p(50.0000) =     ≈ 10⁻⁴ s/op
     p(90.0000) =     ≈ 10⁻⁴ s/op
     p(95.0000) =     ≈ 10⁻⁴ s/op
     p(99.0000) =     ≈ 10⁻⁴ s/op
     p(99.9000) =      0.001 s/op
     p(99.9900) =      0.001 s/op
     p(99.9990) =      0.002 s/op
     p(99.9999) =      0.005 s/op
    p(100.0000) =      0.006 s/op


# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: 20 iterations, 1 s each
# Measurement: 20 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 1 thread, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: com.bazlur.MyBenchmark.testStreamWithSingleFilter

# Run progress: 83.33% complete, ETA 00:06:42
# Fork: 1 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 85.00% complete, ETA 00:06:02
# Fork: 2 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 86.67% complete, ETA 00:05:21
# Fork: 3 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.005 s/op
                 testStreamWithSingleFilter·p1.00:   0.011 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 88.33% complete, ETA 00:04:41
# Fork: 4 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 90.00% complete, ETA 00:04:01
# Fork: 5 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.004 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 91.67% complete, ETA 00:03:21
# Fork: 6 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.005 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.004 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 93.33% complete, ETA 00:02:40
# Fork: 7 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 95.00% complete, ETA 00:02:00
# Fork: 8 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.005 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.004 s/op
                 testStreamWithSingleFilter·p1.00:   0.008 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 96.67% complete, ETA 00:01:20
# Fork: 9 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.003 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op


# Run progress: 98.33% complete, ETA 00:00:40
# Fork: 10 of 10
# Warmup Iteration   1: ≈ 10⁻⁴ s/op
# Warmup Iteration   2: ≈ 10⁻⁵ s/op
# Warmup Iteration   3: ≈ 10⁻⁵ s/op
# Warmup Iteration   4: ≈ 10⁻⁵ s/op
# Warmup Iteration   5: ≈ 10⁻⁵ s/op
# Warmup Iteration   6: ≈ 10⁻⁵ s/op
# Warmup Iteration   7: ≈ 10⁻⁵ s/op
# Warmup Iteration   8: ≈ 10⁻⁵ s/op
# Warmup Iteration   9: ≈ 10⁻⁵ s/op
# Warmup Iteration  10: ≈ 10⁻⁵ s/op
# Warmup Iteration  11: ≈ 10⁻⁵ s/op
# Warmup Iteration  12: ≈ 10⁻⁵ s/op
# Warmup Iteration  13: ≈ 10⁻⁵ s/op
# Warmup Iteration  14: ≈ 10⁻⁵ s/op
# Warmup Iteration  15: ≈ 10⁻⁵ s/op
# Warmup Iteration  16: ≈ 10⁻⁵ s/op
# Warmup Iteration  17: ≈ 10⁻⁵ s/op
# Warmup Iteration  18: ≈ 10⁻⁵ s/op
# Warmup Iteration  19: ≈ 10⁻⁵ s/op
# Warmup Iteration  20: ≈ 10⁻⁵ s/op
Iteration   1: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   2: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   3: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   4: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   5: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   6: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   7: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration   8: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration   9: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op

Iteration  10: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  11: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  12: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  13: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  14: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  0.001 s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  15: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  16: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  17: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  18: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.002 s/op

Iteration  19: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.9999: 0.001 s/op
                 testStreamWithSingleFilter·p1.00:   0.001 s/op

Iteration  20: ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.00:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.50:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.90:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.95:   ≈ 10⁻⁵ s/op
                 testStreamWithSingleFilter·p0.99:   ≈ 10⁻⁴ s/op
                 testStreamWithSingleFilter·p0.999:  ≈ 10⁻³ s/op
                 testStreamWithSingleFilter·p0.9999: 0.002 s/op
                 testStreamWithSingleFilter·p1.00:   0.003 s/op



Result "testStreamWithSingleFilter":
  N = 3292270
  mean =     ≈ 10⁻⁵ ±(99.9%) 0.001 s/op

  Histogram, s/op:
    [0.000, 0.001) = 3292189 
    [0.001, 0.003) = 60 
    [0.003, 0.004) = 15 
    [0.004, 0.005) = 3 
    [0.005, 0.006) = 1 
    [0.006, 0.008) = 0 
    [0.008, 0.009) = 1 
    [0.009, 0.010) = 0 
    [0.010, 0.011) = 1 
    [0.011, 0.013) = 0 
    [0.013, 0.014) = 0 
    [0.014, 0.015) = 0 
    [0.015, 0.016) = 0 
    [0.016, 0.018) = 0 
    [0.018, 0.019) = 0 

  Percentiles, s/op:
      p(0.0000) =     ≈ 10⁻⁵ s/op
     p(50.0000) =     ≈ 10⁻⁵ s/op
     p(90.0000) =     ≈ 10⁻⁵ s/op
     p(95.0000) =     ≈ 10⁻⁵ s/op
     p(99.0000) =     ≈ 10⁻⁴ s/op
     p(99.9000) =     ≈ 10⁻⁴ s/op
     p(99.9900) =      0.001 s/op
     p(99.9990) =      0.002 s/op
     p(99.9999) =      0.005 s/op
    p(100.0000) =      0.011 s/op


# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: <none>
# Measurement: 1 iterations, single-shot each
# Timeout: 10 min per iteration
# Threads: 1 thread
# Benchmark mode: Single shot invocation time
# Benchmark: com.bazlur.MyBenchmark.testStreamWithMultipleFilter

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 1 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 2 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 3 of 10
Iteration   1: 0.010 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 4 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 5 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 6 of 10
Iteration   1: 0.010 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 7 of 10
Iteration   1: 0.011 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 8 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 9 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 10 of 10
Iteration   1: 0.010 s/op


Result "testStreamWithMultipleFilter":
  N = 10
  mean =      0.010 ±(99.9%) 0.001 s/op

  Histogram, s/op:
    [0.009, 0.009) = 1 
    [0.009, 0.010) = 5 
    [0.010, 0.010) = 2 
    [0.010, 0.010) = 0 
    [0.010, 0.010) = 0 
    [0.010, 0.011) = 1 
    [0.011, 0.011) = 0 
    [0.011, 0.011) = 0 
    [0.011, 0.011) = 0 
    [0.011, 0.012) = 1 
    [0.012, 0.012) = 0 

  Percentiles, s/op:
      p(0.0000) =      0.009 s/op
     p(50.0000) =      0.009 s/op
     p(90.0000) =      0.011 s/op
     p(95.0000) =      0.011 s/op
     p(99.0000) =      0.011 s/op
     p(99.9000) =      0.011 s/op
     p(99.9900) =      0.011 s/op
     p(99.9990) =      0.011 s/op
     p(99.9999) =      0.011 s/op
    p(100.0000) =      0.011 s/op


# JMH 1.17.3 (released 15 days ago)
# VM version: JDK 1.8.0_111, VM 25.111-b14
# VM invoker: /usr/lib/jvm/java-8-oracle/jre/bin/java
# VM options: <none>
# Warmup: <none>
# Measurement: 1 iterations, single-shot each
# Timeout: 10 min per iteration
# Threads: 1 thread
# Benchmark mode: Single shot invocation time
# Benchmark: com.bazlur.MyBenchmark.testStreamWithSingleFilter

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 1 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 2 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 3 of 10
Iteration   1: 0.010 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 4 of 10
Iteration   1: 0.010 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 5 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 6 of 10
Iteration   1: 0.008 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 7 of 10
Iteration   1: 0.008 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 8 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 9 of 10
Iteration   1: 0.009 s/op

# Run progress: 100.00% complete, ETA 00:00:00
# Fork: 10 of 10
Iteration   1: 0.008 s/op


Result "testStreamWithSingleFilter":
  N = 10
  mean =      0.009 ±(99.9%) 0.001 s/op

  Histogram, s/op:
    [0.008, 0.008) = 0 
    [0.008, 0.008) = 0 
    [0.008, 0.008) = 1 
    [0.008, 0.009) = 2 
    [0.009, 0.009) = 1 
    [0.009, 0.009) = 1 
    [0.009, 0.009) = 0 
    [0.009, 0.009) = 0 
    [0.009, 0.009) = 1 
    [0.009, 0.009) = 2 
    [0.009, 0.009) = 0 
    [0.009, 0.010) = 0 
    [0.010, 0.010) = 0 
    [0.010, 0.010) = 2 
    [0.010, 0.010) = 0 

  Percentiles, s/op:
      p(0.0000) =      0.008 s/op
     p(50.0000) =      0.009 s/op
     p(90.0000) =      0.010 s/op
     p(95.0000) =      0.010 s/op
     p(99.0000) =      0.010 s/op
     p(99.9000) =      0.010 s/op
     p(99.9900) =      0.010 s/op
     p(99.9990) =      0.010 s/op
     p(99.9999) =      0.010 s/op
    p(100.0000) =      0.010 s/op


# Run complete. Total time: 00:40:19

Benchmark                                                                        Mode      Cnt      Score     Error  Units
MyBenchmark.testStreamWithMultipleFilter                                        thrpt      200  24367.016 ± 169.686  ops/s
MyBenchmark.testStreamWithSingleFilter                                          thrpt      200  32779.157 ± 127.938  ops/s
MyBenchmark.testStreamWithMultipleFilter                                         avgt      200     ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithSingleFilter                                           avgt      200     ≈ 10⁻⁵             s/op
MyBenchmark.testStreamWithMultipleFilter                                       sample  2581418     ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p0.00    sample              ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p0.50    sample              ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p0.90    sample              ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p0.95    sample              ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p0.99    sample              ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p0.999   sample               0.001             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p0.9999  sample               0.001             s/op
MyBenchmark.testStreamWithMultipleFilter:testStreamWithMultipleFilter·p1.00    sample               0.006             s/op
MyBenchmark.testStreamWithSingleFilter                                         sample  3292270     ≈ 10⁻⁵             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p0.00        sample              ≈ 10⁻⁵             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p0.50        sample              ≈ 10⁻⁵             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p0.90        sample              ≈ 10⁻⁵             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p0.95        sample              ≈ 10⁻⁵             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p0.99        sample              ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p0.999       sample              ≈ 10⁻⁴             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p0.9999      sample               0.001             s/op
MyBenchmark.testStreamWithSingleFilter:testStreamWithSingleFilter·p1.00        sample               0.011             s/op
MyBenchmark.testStreamWithMultipleFilter                                           ss       10      0.010 ±   0.001   s/op
MyBenchmark.testStreamWithSingleFilter                                             ss       10      0.009 ±   0.001   s/op
