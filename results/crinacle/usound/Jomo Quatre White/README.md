# Jomo Quatre White
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -10.0; 23 -10.0; 25 -10.1; 28 -10.1; 31 -10.1; 34 -10.0; 37 -10.0; 41 -10.0; 45 -10.0; 49 -10.0; 54 -9.9; 60 -9.9; 66 -10.0; 72 -10.1; 79 -10.2; 87 -10.4; 96 -10.6; 106 -10.7; 116 -10.8; 128 -10.9; 141 -11.0; 155 -11.1; 170 -11.0; 187 -10.9; 206 -10.8; 227 -10.7; 249 -10.5; 274 -10.2; 302 -10.0; 332 -9.7; 365 -9.3; 402 -9.0; 442 -8.7; 486 -8.3; 535 -7.9; 588 -7.4; 647 -6.8; 712 -6.2; 783 -5.5; 861 -4.9; 947 -4.6; 1042 -4.7; 1146 -5.2; 1261 -5.7; 1387 -6.0; 1526 -5.9; 1678 -5.5; 1846 -5.2; 2031 -4.9; 2234 -4.5; 2457 -3.4; 2703 -1.3; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -1.9; 4353 -4.5; 4788 -7.4; 5267 -6.4; 5793 -2.4; 6373 -1.1; 7010 -4.0; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -6.5; 15026 -6.5; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Jomo Quatre White GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Jomo Quatre White ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 23 Hz   | 0.49 | -3.1 dB |
| Peaking | 175 Hz  | 0.41 | -4.3 dB |
| Peaking | 912 Hz  | 1.82 | 2.6 dB  |
| Peaking | 3152 Hz | 2.17 | 6.8 dB  |
| Peaking | 6313 Hz | 6.58 | 5.6 dB  |
| Peaking | 3955 Hz | 5.83 | 2.0 dB  |
| Peaking | 4995 Hz | 4.36 | -3.6 dB |
| Peaking | 5741 Hz | 6.31 | 2.3 dB  |
| Peaking | 8470 Hz | 3.93 | -0.5 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-5.3dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -3.6 dB |
| Peaking | 62 Hz    | 1.41 | -2.3 dB |
| Peaking | 125 Hz   | 1.41 | -3.6 dB |
| Peaking | 250 Hz   | 1.41 | -3.5 dB |
| Peaking | 500 Hz   | 1.41 | -1.3 dB |
| Peaking | 1000 Hz  | 1.41 | 1.5 dB  |
| Peaking | 2000 Hz  | 1.41 | 1.2 dB  |
| Peaking | 4000 Hz  | 1.41 | 4.5 dB  |
| Peaking | 8000 Hz  | 1.41 | 0.3 dB  |
| Peaking | 16000 Hz | 1.41 | -0.2 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Jomo%20Quatre%20White/Jomo%20Quatre%20White.png)