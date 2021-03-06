# Noble Audio Django
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -7.8; 23 -7.9; 25 -8.1; 28 -8.2; 31 -8.4; 34 -8.6; 37 -8.7; 41 -8.9; 45 -9.1; 49 -9.2; 54 -9.5; 60 -9.7; 66 -10.1; 72 -10.4; 79 -10.8; 87 -11.2; 96 -11.7; 106 -12.1; 116 -12.4; 128 -12.7; 141 -13.0; 155 -13.3; 170 -13.4; 187 -13.5; 206 -13.5; 227 -13.5; 249 -13.4; 274 -13.3; 302 -13.1; 332 -12.7; 365 -12.3; 402 -12.1; 442 -11.7; 486 -11.3; 535 -10.8; 588 -10.2; 647 -9.6; 712 -8.9; 783 -8.1; 861 -7.4; 947 -7.0; 1042 -6.8; 1146 -6.8; 1261 -6.6; 1387 -5.8; 1526 -4.4; 1678 -2.7; 1846 -0.9; 2031 -0.5; 2234 -0.5; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.9; 5793 -3.4; 6373 -2.2; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -7.7; 15026 -17.0; 16529 -22.9; 18182 -23.4; 20000 -19.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Noble Audio Django GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Noble Audio Django ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.2dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 46 Hz    | 0.29 | -1.3 dB  |
| Peaking | 156 Hz   | 0.59 | -2.6 dB  |
| Peaking | 431 Hz   | 0.3  | -5.6 dB  |
| Peaking | 7898 Hz  | 0.13 | 9.6 dB   |
| Peaking | 17818 Hz | 0.45 | -25.3 dB |
| Peaking | 1340 Hz  | 3.52 | -2.1 dB  |
| Peaking | 1951 Hz  | 3.09 | 1.8 dB   |
| Peaking | 8084 Hz  | 2.81 | -3.0 dB  |
| Peaking | 13331 Hz | 2.39 | 5.7 dB   |
| Peaking | 15693 Hz | 2.67 | -4.7 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -1.5 dB  |
| Peaking | 62 Hz    | 1.41 | -2.2 dB  |
| Peaking | 125 Hz   | 1.41 | -5.1 dB  |
| Peaking | 250 Hz   | 1.41 | -6.1 dB  |
| Peaking | 500 Hz   | 1.41 | -3.6 dB  |
| Peaking | 1000 Hz  | 1.41 | -1.1 dB  |
| Peaking | 2000 Hz  | 1.41 | 5.1 dB   |
| Peaking | 4000 Hz  | 1.41 | 6.1 dB   |
| Peaking | 8000 Hz  | 1.41 | 2.5 dB   |
| Peaking | 16000 Hz | 1.41 | -17.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Noble%20Audio%20Django/Noble%20Audio%20Django.png)