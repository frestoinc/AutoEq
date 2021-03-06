# Shozy & Neo BG
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -3.5; 23 -4.0; 25 -4.4; 28 -4.8; 31 -5.1; 34 -5.4; 37 -5.6; 41 -5.9; 45 -6.1; 49 -6.4; 54 -6.7; 60 -6.9; 66 -7.2; 72 -7.6; 79 -7.9; 87 -8.3; 96 -8.6; 106 -9.1; 116 -9.3; 128 -9.5; 141 -9.7; 155 -9.8; 170 -9.9; 187 -10.0; 206 -10.0; 227 -9.8; 249 -9.6; 274 -9.4; 302 -9.2; 332 -8.8; 365 -8.5; 402 -8.1; 442 -7.8; 486 -7.4; 535 -6.9; 588 -6.4; 647 -6.0; 712 -5.4; 783 -4.9; 861 -4.6; 947 -4.5; 1042 -4.8; 1146 -5.7; 1261 -6.7; 1387 -7.6; 1526 -8.1; 1678 -8.6; 1846 -9.0; 2031 -8.0; 2234 -5.4; 2457 -2.6; 2703 -1.5; 2973 -2.3; 3270 -4.0; 3597 -3.9; 3957 -0.8; 4353 -0.5; 4788 -0.5; 5267 -2.2; 5793 -5.3; 6373 -8.0; 7010 -6.8; 7711 -8.7; 8482 -8.0; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.9; 18182 -8.1; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Shozy & Neo BG GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Shozy & Neo BG ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 18 Hz    | 0.89 | 3.3 dB  |
| Peaking | 172 Hz   | 0.73 | -3.8 dB |
| Peaking | 2712 Hz  | 5.65 | 4.9 dB  |
| Peaking | 4616 Hz  | 2.25 | 7.7 dB  |
| Peaking | 6759 Hz  | 1.58 | -3.0 dB |
| Peaking | 349 Hz   | 1.95 | -0.8 dB |
| Peaking | 898 Hz   | 1.74 | 2.7 dB  |
| Peaking | 1812 Hz  | 2    | -3.7 dB |
| Peaking | 2379 Hz  | 4.45 | 2.5 dB  |
| Peaking | 17847 Hz | 3.38 | -2.1 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-6.7dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 2.0 dB  |
| Peaking | 62 Hz    | 1.41 | -0.5 dB |
| Peaking | 125 Hz   | 1.41 | -2.7 dB |
| Peaking | 250 Hz   | 1.41 | -3.1 dB |
| Peaking | 500 Hz   | 1.41 | -0.2 dB |
| Peaking | 1000 Hz  | 1.41 | 1.8 dB  |
| Peaking | 2000 Hz  | 1.41 | -2.3 dB |
| Peaking | 4000 Hz  | 1.41 | 6.9 dB  |
| Peaking | 8000 Hz  | 1.41 | -2.4 dB |
| Peaking | 16000 Hz | 1.41 | -0.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Shozy%20&%20Neo%20BG/Shozy%20&%20Neo%20BG.png)