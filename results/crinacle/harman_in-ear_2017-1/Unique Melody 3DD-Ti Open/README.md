# Unique Melody 3DD-Ti Open
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -8.1; 23 -8.1; 25 -8.2; 28 -8.1; 31 -8.1; 34 -8.0; 37 -7.9; 41 -7.8; 45 -7.7; 49 -7.6; 54 -7.5; 60 -7.4; 66 -7.3; 72 -7.4; 79 -7.4; 87 -7.4; 96 -7.5; 106 -7.7; 116 -7.7; 128 -7.8; 141 -7.8; 155 -7.8; 170 -7.7; 187 -7.7; 206 -7.6; 227 -7.5; 249 -7.4; 274 -7.2; 302 -7.0; 332 -6.7; 365 -6.4; 402 -6.1; 442 -5.9; 486 -5.6; 535 -5.4; 588 -5.3; 647 -5.3; 712 -5.7; 783 -6.3; 861 -7.0; 947 -8.1; 1042 -9.7; 1146 -11.4; 1261 -12.6; 1387 -12.6; 1526 -11.2; 1678 -9.0; 1846 -6.6; 2031 -4.3; 2234 -2.6; 2457 -1.9; 2703 -3.0; 2973 -8.1; 3270 -12.4; 3597 -6.3; 3957 -1.7; 4353 -0.5; 4788 -0.8; 5267 -2.4; 5793 -7.9; 6373 -8.9; 7010 -4.3; 7711 -6.2; 8482 -6.5; 9330 -7.9; 10263 -6.7; 11289 -6.5; 12418 -6.5; 13660 -6.9; 15026 -15.6; 16529 -22.5; 18182 -21.2; 20000 -11.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Unique Melody 3DD-Ti Open GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Unique Melody 3DD-Ti Open ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.8dB**.

| Type    | Fc       |     Q | Gain     |
|:--------|:---------|:------|:---------|
| Peaking | 1351 Hz  |  2.44 | -7.6 dB  |
| Peaking | 2489 Hz  |  2.05 | 6.3 dB   |
| Peaking | 3223 Hz  |  5.28 | -10.6 dB |
| Peaking | 4350 Hz  |  2.85 | 7.2 dB   |
| Peaking | 17513 Hz |  1.37 | -18.6 dB |
| Peaking | 49 Hz    |  0.04 | -1.2 dB  |
| Peaking | 574 Hz   |  1.28 | 2.6 dB   |
| Peaking | 6096 Hz  | 12.21 | -5.3 dB  |
| Peaking | 13614 Hz |  1.52 | 5.6 dB   |
| Peaking | 15559 Hz |  2.5  | -7.1 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -1.8 dB  |
| Peaking | 62 Hz    | 1.41 | -0.4 dB  |
| Peaking | 125 Hz   | 1.41 | -1.1 dB  |
| Peaking | 250 Hz   | 1.41 | -1.3 dB  |
| Peaking | 500 Hz   | 1.41 | 2.8 dB   |
| Peaking | 1000 Hz  | 1.41 | -4.5 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.3 dB   |
| Peaking | 4000 Hz  | 1.41 | 3.0 dB   |
| Peaking | 8000 Hz  | 1.41 | 1.5 dB   |
| Peaking | 16000 Hz | 1.41 | -15.0 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Unique%20Melody%203DD-Ti%20Open/Unique%20Melody%203DD-Ti%20Open.png)