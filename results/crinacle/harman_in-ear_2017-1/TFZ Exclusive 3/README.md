# TFZ Exclusive 3
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -12.7; 23 -12.8; 25 -12.8; 28 -12.7; 31 -12.7; 34 -12.6; 37 -12.5; 41 -12.4; 45 -12.3; 49 -12.2; 54 -12.0; 60 -11.9; 66 -11.8; 72 -11.7; 79 -11.7; 87 -11.6; 96 -11.5; 106 -11.4; 116 -11.3; 128 -11.1; 141 -10.9; 155 -10.6; 170 -10.2; 187 -9.9; 206 -9.4; 227 -8.9; 249 -8.5; 274 -8.0; 302 -7.4; 332 -6.8; 365 -6.2; 402 -5.7; 442 -5.2; 486 -4.7; 535 -4.2; 588 -3.8; 647 -3.4; 712 -2.9; 783 -2.5; 861 -2.3; 947 -2.5; 1042 -3.3; 1146 -4.3; 1261 -5.1; 1387 -5.5; 1526 -5.7; 1678 -5.9; 1846 -6.2; 2031 -6.6; 2234 -6.9; 2457 -6.4; 2703 -4.7; 2973 -2.5; 3270 -1.0; 3597 -0.5; 3957 -1.2; 4353 -3.3; 4788 -8.0; 5267 -11.3; 5793 -5.4; 6373 -1.2; 7010 -3.1; 7711 -5.3; 8482 -5.6; 9330 -5.6; 10263 -5.6; 11289 -5.6; 12418 -5.6; 13660 -10.9; 15026 -18.8; 16529 -22.4; 18182 -19.4; 20000 -8.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`TFZ Exclusive 3 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `TFZ Exclusive 3 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.3dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 25 Hz    | 0.11 | -7.0 dB  |
| Peaking | 709 Hz   | 1.41 | 3.7 dB   |
| Peaking | 5194 Hz  | 7.46 | -9.9 dB  |
| Peaking | 10616 Hz | 0.34 | 7.4 dB   |
| Peaking | 16613 Hz | 0.79 | -22.8 dB |
| Peaking | 2242 Hz  | 1.97 | -3.3 dB  |
| Peaking | 3375 Hz  | 2.91 | 4.2 dB   |
| Peaking | 8473 Hz  | 3.75 | -2.5 dB  |
| Peaking | 12695 Hz | 3.74 | 4.0 dB   |
| Peaking | 14735 Hz | 4.03 | -3.0 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.2dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -7.5 dB  |
| Peaking | 62 Hz    | 1.41 | -4.5 dB  |
| Peaking | 125 Hz   | 1.41 | -4.6 dB  |
| Peaking | 250 Hz   | 1.41 | -2.5 dB  |
| Peaking | 500 Hz   | 1.41 | 1.6 dB   |
| Peaking | 1000 Hz  | 1.41 | 2.8 dB   |
| Peaking | 2000 Hz  | 1.41 | -1.9 dB  |
| Peaking | 4000 Hz  | 1.41 | 2.8 dB   |
| Peaking | 8000 Hz  | 1.41 | 2.5 dB   |
| Peaking | 16000 Hz | 1.41 | -17.9 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/TFZ%20Exclusive%203/TFZ%20Exclusive%203.png)