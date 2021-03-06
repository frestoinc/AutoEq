# Unique Melody ME1
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.6; 31 -1.0; 34 -1.5; 37 -1.9; 41 -2.3; 45 -2.8; 49 -3.2; 54 -3.6; 60 -4.1; 66 -4.6; 72 -5.1; 79 -5.6; 87 -6.2; 96 -6.8; 106 -7.4; 116 -7.9; 128 -8.3; 141 -8.8; 155 -9.2; 170 -9.6; 187 -9.9; 206 -10.1; 227 -10.3; 249 -10.5; 274 -10.7; 302 -10.8; 332 -10.9; 365 -11.0; 402 -11.2; 442 -11.4; 486 -11.6; 535 -11.8; 588 -12.0; 647 -12.3; 712 -12.5; 783 -12.5; 861 -12.4; 947 -12.1; 1042 -11.7; 1146 -11.3; 1261 -11.0; 1387 -10.5; 1526 -9.2; 1678 -7.1; 1846 -5.2; 2031 -2.9; 2234 -0.7; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -1.6; 4353 -2.9; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -2.1; 7010 -4.1; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -7.7; 15026 -17.1; 16529 -20.3; 18182 -16.9; 20000 -9.7
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Unique Melody ME1 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Unique Melody ME1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 25 Hz    | 0.58 | 6.2 dB   |
| Peaking | 971 Hz   | 0.19 | -6.6 dB  |
| Peaking | 2410 Hz  | 1.58 | 8.8 dB   |
| Peaking | 4750 Hz  | 0.77 | 8.0 dB   |
| Peaking | 16966 Hz | 1.25 | -15.2 dB |
| Peaking | 2579 Hz  | 7.04 | -0.7 dB  |
| Peaking | 3297 Hz  | 5.27 | 1.0 dB   |
| Peaking | 7889 Hz  | 6.11 | -2.0 dB  |
| Peaking | 12908 Hz | 3.26 | 4.6 dB   |
| Peaking | 18138 Hz | 0.37 | -1.4 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.5dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | 6.4 dB   |
| Peaking | 62 Hz    | 1.41 | 1.5 dB   |
| Peaking | 125 Hz   | 1.41 | -1.7 dB  |
| Peaking | 250 Hz   | 1.41 | -3.4 dB  |
| Peaking | 500 Hz   | 1.41 | -3.8 dB  |
| Peaking | 1000 Hz  | 1.41 | -6.9 dB  |
| Peaking | 2000 Hz  | 1.41 | 3.6 dB   |
| Peaking | 4000 Hz  | 1.41 | 6.5 dB   |
| Peaking | 8000 Hz  | 1.41 | 2.0 dB   |
| Peaking | 16000 Hz | 1.41 | -14.0 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Unique%20Melody%20ME1/Unique%20Melody%20ME1.png)