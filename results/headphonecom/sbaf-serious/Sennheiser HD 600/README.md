# Sennheiser HD 600
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -0.5; 23 -0.5; 25 -0.5; 28 -0.5; 31 -0.5; 34 -0.5; 37 -0.5; 41 -1.0; 45 -1.6; 49 -2.1; 54 -2.1; 60 -2.3; 66 -3.8; 72 -4.7; 79 -5.2; 87 -5.8; 96 -6.2; 106 -6.6; 116 -6.8; 128 -7.2; 141 -7.1; 155 -7.4; 170 -7.5; 187 -7.3; 206 -7.3; 227 -7.1; 249 -7.1; 274 -6.8; 302 -6.5; 332 -6.3; 365 -6.0; 402 -5.7; 442 -5.4; 486 -5.3; 535 -5.4; 588 -5.2; 647 -5.0; 712 -4.8; 783 -4.9; 861 -5.2; 947 -5.5; 1042 -5.4; 1146 -5.4; 1261 -5.6; 1387 -6.0; 1526 -6.3; 1678 -6.3; 1846 -6.4; 2031 -6.4; 2234 -6.9; 2457 -7.2; 2703 -7.6; 2973 -8.2; 3270 -9.4; 3597 -10.0; 3957 -9.9; 4353 -10.2; 4788 -9.9; 5267 -7.1; 5793 -3.2; 6373 -4.0; 7010 -4.6; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -10.1; 15026 -11.1; 16529 -7.2; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 600 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 600 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.1dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 0.92 | 6.9 dB  |
| Peaking | 784 Hz   | 1.13 | 1.7 dB  |
| Peaking | 4528 Hz  | 1.47 | -5.8 dB |
| Peaking | 5940 Hz  | 2.62 | 6.6 dB  |
| Peaking | 14655 Hz | 3.21 | -5.5 dB |
| Peaking | 35 Hz    | 3.54 | -0.4 dB |
| Peaking | 58 Hz    | 3.57 | 1.9 dB  |
| Peaking | 149 Hz   | 1.08 | -1.4 dB |
| Peaking | 10932 Hz | 4.38 | 0.4 dB  |
| Peaking | 12438 Hz | 8.31 | 0.9 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 7.1 dB  |
| Peaking | 62 Hz    | 1.41 | 2.2 dB  |
| Peaking | 125 Hz   | 1.41 | -1.4 dB |
| Peaking | 250 Hz   | 1.41 | -0.8 dB |
| Peaking | 500 Hz   | 1.41 | 1.4 dB  |
| Peaking | 1000 Hz  | 1.41 | 1.2 dB  |
| Peaking | 2000 Hz  | 1.41 | 0.2 dB  |
| Peaking | 4000 Hz  | 1.41 | -3.6 dB |
| Peaking | 8000 Hz  | 1.41 | 2.2 dB  |
| Peaking | 16000 Hz | 1.41 | -3.5 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Sennheiser%20HD%20600/Sennheiser%20HD%20600.png)