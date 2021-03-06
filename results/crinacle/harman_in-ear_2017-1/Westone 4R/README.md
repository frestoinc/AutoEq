# Westone 4R
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -3.1; 23 -3.8; 25 -4.5; 28 -5.4; 31 -6.1; 34 -6.6; 37 -7.1; 41 -7.6; 45 -8.1; 49 -8.5; 54 -9.0; 60 -9.4; 66 -9.9; 72 -10.4; 79 -10.9; 87 -11.4; 96 -11.9; 106 -12.3; 116 -12.8; 128 -13.2; 141 -13.5; 155 -13.7; 170 -13.8; 187 -14.0; 206 -14.1; 227 -14.0; 249 -13.9; 274 -13.8; 302 -13.5; 332 -13.1; 365 -12.7; 402 -12.3; 442 -11.8; 486 -11.3; 535 -10.6; 588 -9.9; 647 -9.1; 712 -8.3; 783 -7.5; 861 -6.8; 947 -6.5; 1042 -6.6; 1146 -7.0; 1261 -7.1; 1387 -6.6; 1526 -5.5; 1678 -4.1; 1846 -2.5; 2031 -0.7; 2234 -0.5; 2457 -0.5; 2703 -0.5; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.5; 4788 -0.5; 5267 -0.5; 5793 -0.5; 6373 -1.0; 7010 -4.0; 7711 -7.0; 8482 -6.7; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -11.6; 15026 -20.3; 16529 -27.9; 18182 -28.2; 20000 -12.4
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Westone 4R GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Westone 4R ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.2dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 15 Hz    | 0.86 | 5.7 dB   |
| Peaking | 205 Hz   | 0.55 | -3.9 dB  |
| Peaking | 293 Hz   | 0.17 | -4.1 dB  |
| Peaking | 7201 Hz  | 0.18 | 10.0 dB  |
| Peaking | 17252 Hz | 0.69 | -30.6 dB |
| Peaking | 1380 Hz  | 2.06 | -5.7 dB  |
| Peaking | 1435 Hz  | 0.94 | 3.5 dB   |
| Peaking | 7954 Hz  | 4.57 | -4.2 dB  |
| Peaking | 12709 Hz | 2.9  | 5.0 dB   |
| Peaking | 15521 Hz | 3.19 | -3.7 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-8.0dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | 1.7 dB   |
| Peaking | 62 Hz    | 1.41 | -2.6 dB  |
| Peaking | 125 Hz   | 1.41 | -5.5 dB  |
| Peaking | 250 Hz   | 1.41 | -6.7 dB  |
| Peaking | 500 Hz   | 1.41 | -3.4 dB  |
| Peaking | 1000 Hz  | 1.41 | -0.7 dB  |
| Peaking | 2000 Hz  | 1.41 | 4.0 dB   |
| Peaking | 4000 Hz  | 1.41 | 6.8 dB   |
| Peaking | 8000 Hz  | 1.41 | 4.0 dB   |
| Peaking | 16000 Hz | 1.41 | -22.8 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Westone%204R/Westone%204R.png)