:hotel: [Return to Home Page](https://github.com/geophydog/geophydog.github.io/blob/master/README.md)

***

# Time-frequency-analysis
- Executing time-frequency analysis with short time FFT method.

***

## Installation
- Execute 'make' to compile executable command 'time-fre'.

***

## Dependencies
- Linux or Mac OS platform.
- GMT (the Generic Mapping Tools, here, version 5.3.1).
   - [Download GMT](http://gmt.soest.hawaii.edu/projects/gmt/wiki/Download)

***

## Usage
- time-fre SACfile t1 t2 segment_length fre_low fre_high output_file

| parameter | mean | 
| --------- | ---- |
| SACfile   | name of SAC format file |
|    t1     | begin time of doing time-frequency analysis |
|    t2     | end time of doing time-frequency analysis   |
|  segment_length |  segment length of doing time-frequency |
|  fre_low   |  low limitation of corner frequency of doing time-frequency analysis |
|  fre_high  | high limitation of corner frequency of doing time-frequency analysis |
|  output_file | file name of outputting results |

## Example
```
Go the directory "Example" and run with command below.
```

```
time-fre ft_BBR.BHZ.SAC 0 30000 50 0.005 0.2 out.txt
```
__result__
![result](https://github.com/geophydog/Time-frequency-analysis/blob/master/Example/ft_BBR.BHZ.SAC.png)

## Contribution
- Author: Xuping Feng
- Email: geophydogvon@gmail.com
