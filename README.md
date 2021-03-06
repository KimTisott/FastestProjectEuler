#### My overly optimized solutions of [Project Euler](https://projecteuler.net) problems, focused on math algorithms and code efficiency

# Benchmark

```
BenchmarkDotNet=v0.13.1, OS=Windows 10.0.19042.1165 (20H2/October2020Update)
Intel Core i5-10300H CPU 2.50GHz, 1 CPU, 8 logical and 4 physical cores
.NET SDK=5.0.301
  [Host]     : .NET 5.0.7 (5.0.721.25508), X64 RyuJIT
  DefaultJob : .NET 5.0.7 (5.0.721.25508), X64 RyuJIT
```

| Problem                                   | Solution                                                                         | Mean (ns)      | Error (ns)   | StdDev (ns)  | Alloc (B) | Code (B) |
| :---------------------------------------: | :------------------------------------------------------------------------------: | -------------: | -----------: | -----------: | --------: | -------: |
| [1](https://projecteuler.net/problem=1)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem1.cs)  |          7.145 |       0.0464 |       0.0411 |           |      114 |
| [2](https://projecteuler.net/problem=2)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem2.cs)  |          2.252 |       0.0358 |       0.0299 |           |       41 |
| [3](https://projecteuler.net/problem=3)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem3.cs)  |      2,959.334 |       6.4148 |       5.6866 |           |      296 |
| [4](https://projecteuler.net/problem=4)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem4.cs)  |      4,985.330 |      84.6668 |      70.7006 |           |      288 |
| [5](https://projecteuler.net/problem=5)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem5.cs)  |        369.928 |       2.7705 |       2.5915 |           |       67 |
| [6](https://projecteuler.net/problem=6)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem6.cs)  |          2.711 |       0.0785 |       0.0656 |           |       40 |
| [7](https://projecteuler.net/problem=7)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem7.cs)  |    183,786.575 |   4,719.0404 |  13,914.1970 |   105,464 |      451 |
| [8](https://projecteuler.net/problem=8)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem8.cs)  |      5,482.294 |      33.3278 |      29.5443 |           |      125 |
| [9](https://projecteuler.net/problem=9)   | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem9.cs)  |         43.824 |       0.6692 |       0.6260 |           |      199 |
| [10](https://projecteuler.net/problem=10) | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem10.cs) |  4,586,937.003 |  79,902.3394 |  98,127.2485 | 2,000,024 |      191 |
| [11](https://projecteuler.net/problem=11) | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem11.cs) |      3,729.953 |      45.9832 |      43.0127 |           |    1,113 |
| [12](https://projecteuler.net/problem=12) | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem12.cs) | 10,231,712.240 |  41,283.6572 |  38,616.7585 |           |      179 |
| [13](https://projecteuler.net/problem=13) | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem13.cs) |      2,706.707 |      23.1532 |      20.5247 |     4,896 |    2,290 |
| [14](https://projecteuler.net/problem=14) | [C#](https://github.com/KimTisott/ProjectEuler/blob/main/Solutions/Problem14.cs) | 12,208,562.518 | 273,230.6109 | 738,694.8445 | 8,000,020 |      239 |

#### Legend
- ns: nanosecond (10<sup>-9</sup> second)
- B : byte

Suggetions and performance improvements are welcome. Submit them [here](https://github.com/KimTisott/ProjectEuler/issues/new).

### References

<a href="https://projecteuler.net">
  <img src="https://projecteuler.net/themes/20210213/logo_default.png">
</a>
<a href="https://projecteuler.chat">
  <img src="https://projecteuler.chat/ext/euler13/pechat/styles/prosilver/theme/images/site_logo.png">
</a>
<a href="https://mathoverflow.net">
  <img src="https://cdn.sstatic.net/Sites/mathoverflow/Img/logo.svg?v=3a674b060adf">
</a>

### Contact Information

<a href="https://www.linkedin.com/in/kim-tisott-58133815b">
  <img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Linkedin_unofficial_colored_svg-64.png">
</a>
<a href="https://www.hackerrank.com/kim_nicolay">
  <img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/160_Hackerrank_logo_logos-64.png">
</a>
