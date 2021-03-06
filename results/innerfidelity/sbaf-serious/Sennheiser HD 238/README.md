# Sennheiser HD 238
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -1.2; 25 -1.7; 28 -2.3; 31 -2.8; 34 -3.3; 37 -3.7; 41 -4.1; 45 -4.4; 49 -4.7; 54 -5.1; 60 -5.4; 66 -5.7; 72 -6.1; 79 -6.3; 87 -6.8; 96 -7.3; 106 -7.7; 116 -7.8; 128 -8.1; 141 -8.1; 155 -8.1; 170 -8.0; 187 -8.0; 206 -7.9; 227 -7.5; 249 -7.3; 274 -7.0; 302 -6.8; 332 -6.4; 365 -6.1; 402 -5.7; 442 -5.3; 486 -5.1; 535 -4.8; 588 -4.3; 647 -4.2; 712 -4.1; 783 -3.7; 861 -3.8; 947 -3.7; 1042 -3.1; 1146 -2.9; 1261 -3.7; 1387 -4.4; 1526 -4.7; 1678 -4.9; 1846 -4.4; 2031 -3.3; 2234 -1.9; 2457 -0.5; 2703 -2.4; 2973 -4.6; 3270 -6.9; 3597 -3.3; 3957 -1.1; 4353 -6.8; 4788 -6.6; 5267 -4.0; 5793 -4.2; 6373 -4.9; 7010 -3.4; 7711 -4.9; 8482 -6.0; 9330 -7.1; 10263 -5.2; 11289 -5.2; 12418 -5.2; 13660 -5.2; 15026 -5.2; 16529 -5.2; 18182 -5.2; 20000 -5.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 238 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 238 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.0dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 14 Hz    | 0.64 | 6.1 dB  |
| Peaking | 153 Hz   | 0.62 | -3.2 dB |
| Peaking | 889 Hz   | 1.01 | 2.0 dB  |
| Peaking | 2422 Hz  | 4.76 | 4.6 dB  |
| Peaking | 22049 Hz | 2.29 | 0.2 dB  |
| Peaking | 3301 Hz  | 6.86 | -3.8 dB |
| Peaking | 3896 Hz  | 5.34 | 5.4 dB  |
| Peaking | 4491 Hz  | 5.98 | -4.9 dB |
| Peaking | 6307 Hz  | 1.03 | 1.2 dB  |
| Peaking | 9105 Hz  | 5.1  | -2.9 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-3.6dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 3.2 dB  |
| Peaking | 62 Hz    | 1.41 | -0.6 dB |
| Peaking | 125 Hz   | 1.41 | -2.7 dB |
| Peaking | 250 Hz   | 1.41 | -2.1 dB |
| Peaking | 500 Hz   | 1.41 | 0.5 dB  |
| Peaking | 1000 Hz  | 1.41 | 1.3 dB  |
| Peaking | 2000 Hz  | 1.41 | 1.8 dB  |
| Peaking | 4000 Hz  | 1.41 | 0.6 dB  |
| Peaking | 8000 Hz  | 1.41 | -0.3 dB |
| Peaking | 16000 Hz | 1.41 | -0.0 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20238/Sennheiser%20HD%20238.png)