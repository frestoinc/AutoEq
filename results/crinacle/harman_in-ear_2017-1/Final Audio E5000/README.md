# Final Audio E5000
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -10.4; 23 -10.9; 25 -11.3; 28 -11.8; 31 -12.2; 34 -12.5; 37 -12.7; 41 -12.9; 45 -13.0; 49 -13.1; 54 -13.2; 60 -13.3; 66 -13.4; 72 -13.5; 79 -13.6; 87 -13.7; 96 -13.7; 106 -13.8; 116 -13.7; 128 -13.6; 141 -13.5; 155 -13.3; 170 -13.0; 187 -12.7; 206 -12.4; 227 -12.1; 249 -11.7; 274 -11.3; 302 -10.9; 332 -10.3; 365 -9.9; 402 -9.4; 442 -9.1; 486 -8.7; 535 -8.2; 588 -7.8; 647 -7.4; 712 -6.9; 783 -6.6; 861 -6.4; 947 -6.3; 1042 -6.5; 1146 -7.0; 1261 -7.4; 1387 -7.3; 1526 -6.9; 1678 -6.4; 1846 -5.8; 2031 -5.0; 2234 -4.1; 2457 -3.5; 2703 -3.2; 2973 -3.2; 3270 -2.9; 3597 -2.3; 3957 -1.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -11.6; 15026 -21.8; 16529 -23.4; 18182 -17.4; 20000 -7.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Final Audio E5000 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Final Audio E5000 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.9dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 39 Hz    | 0.47 | -5.0 dB  |
| Peaking | 155 Hz   | 0.49 | -5.7 dB  |
| Peaking | 1447 Hz  | 3.26 | -1.7 dB  |
| Peaking | 4904 Hz  | 0.7  | 6.3 dB   |
| Peaking | 16433 Hz | 1.41 | -19.4 dB |
| Peaking | 824 Hz   | 3.61 | 0.8 dB   |
| Peaking | 6331 Hz  | 3.35 | 2.7 dB   |
| Peaking | 7563 Hz  | 2.38 | -3.5 dB  |
| Peaking | 12863 Hz | 2.36 | 5.7 dB   |
| Peaking | 14766 Hz | 3.61 | -6.1 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.9dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -5.3 dB  |
| Peaking | 62 Hz    | 1.41 | -5.4 dB  |
| Peaking | 125 Hz   | 1.41 | -5.9 dB  |
| Peaking | 250 Hz   | 1.41 | -4.3 dB  |
| Peaking | 500 Hz   | 1.41 | -1.0 dB  |
| Peaking | 1000 Hz  | 1.41 | -0.1 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.0 dB   |
| Peaking | 4000 Hz  | 1.41 | 6.3 dB   |
| Peaking | 8000 Hz  | 1.41 | 3.2 dB   |
| Peaking | 16000 Hz | 1.41 | -18.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Final%20Audio%20E5000/Final%20Audio%20E5000.png)