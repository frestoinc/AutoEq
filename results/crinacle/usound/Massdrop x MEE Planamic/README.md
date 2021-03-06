# Massdrop x MEE Planamic
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -6.4; 23 -6.8; 25 -7.1; 28 -7.6; 31 -7.9; 34 -8.2; 37 -8.4; 41 -8.7; 45 -9.0; 49 -9.2; 54 -9.4; 60 -9.7; 66 -10.0; 72 -10.3; 79 -10.6; 87 -10.9; 96 -11.2; 106 -11.4; 116 -11.6; 128 -11.7; 141 -11.7; 155 -11.7; 170 -11.6; 187 -11.4; 206 -11.1; 227 -10.8; 249 -10.4; 274 -9.9; 302 -9.5; 332 -8.9; 365 -8.4; 402 -7.8; 442 -7.2; 486 -6.7; 535 -6.1; 588 -5.5; 647 -4.8; 712 -4.1; 783 -3.4; 861 -2.9; 947 -2.6; 1042 -2.7; 1146 -3.4; 1261 -4.3; 1387 -5.1; 1526 -5.8; 1678 -6.2; 1846 -6.5; 2031 -6.8; 2234 -7.0; 2457 -7.7; 2703 -8.1; 2973 -8.0; 3270 -7.8; 3597 -8.3; 3957 -9.9; 4353 -10.5; 4788 -6.5; 5267 -1.7; 5793 -0.5; 6373 -1.0; 7010 -3.9; 7711 -6.2; 8482 -6.4; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -7.0; 15026 -9.0; 16529 -9.9; 18182 -13.5; 20000 -14.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Massdrop x MEE Planamic GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Massdrop x MEE Planamic ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.1dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 85 Hz    | 0.52 | -2.8 dB |
| Peaking | 186 Hz   | 0.66 | -3.6 dB |
| Peaking | 916 Hz   | 1.28 | 4.5 dB  |
| Peaking | 4738 Hz  | 1.14 | -8.1 dB |
| Peaking | 5670 Hz  | 2.3  | 13.5 dB |
| Peaking | 3465 Hz  | 5.25 | 1.4 dB  |
| Peaking | 4232 Hz  | 9.84 | -1.9 dB |
| Peaking | 12469 Hz | 1.55 | 1.4 dB  |
| Peaking | 19379 Hz | 0.62 | -8.4 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-4.6dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | -0.8 dB |
| Peaking | 62 Hz    | 1.41 | -2.7 dB |
| Peaking | 125 Hz   | 1.41 | -4.7 dB |
| Peaking | 250 Hz   | 1.41 | -3.6 dB |
| Peaking | 500 Hz   | 1.41 | 0.2 dB  |
| Peaking | 1000 Hz  | 1.41 | 4.5 dB  |
| Peaking | 2000 Hz  | 1.41 | -1.4 dB |
| Peaking | 4000 Hz  | 1.41 | -1.6 dB |
| Peaking | 8000 Hz  | 1.41 | 3.1 dB  |
| Peaking | 16000 Hz | 1.41 | -4.9 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/usound/Massdrop%20x%20MEE%20Planamic/Massdrop%20x%20MEE%20Planamic.png)