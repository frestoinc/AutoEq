# NocturnaL Audio Atlantis
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -4.3; 23 -4.7; 25 -5.1; 28 -5.6; 31 -6.0; 34 -6.3; 37 -6.5; 41 -6.8; 45 -7.0; 49 -7.3; 54 -7.6; 60 -7.9; 66 -8.2; 72 -8.6; 79 -8.9; 87 -9.4; 96 -9.8; 106 -10.2; 116 -10.5; 128 -10.8; 141 -11.1; 155 -11.3; 170 -11.4; 187 -11.6; 206 -11.6; 227 -11.6; 249 -11.5; 274 -11.4; 302 -11.2; 332 -10.8; 365 -10.5; 402 -10.2; 442 -9.9; 486 -9.6; 535 -9.2; 588 -8.7; 647 -8.3; 712 -7.8; 783 -7.2; 861 -6.8; 947 -6.6; 1042 -6.8; 1146 -7.2; 1261 -7.4; 1387 -7.4; 1526 -7.0; 1678 -6.4; 1846 -5.5; 2031 -4.3; 2234 -3.2; 2457 -2.3; 2703 -0.7; 2973 -0.5; 3270 -0.5; 3597 -0.5; 3957 -0.5; 4353 -0.7; 4788 -1.3; 5267 -3.5; 5793 -4.3; 6373 -6.6; 7010 -5.1; 7711 -6.2; 8482 -6.5; 9330 -6.5; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -7.7; 15026 -11.1; 16529 -6.5; 18182 -6.5; 20000 -6.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`NocturnaL Audio Atlantis GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `NocturnaL Audio Atlantis ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-7.0dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 17 Hz    | 1.06 | 2.9 dB  |
| Peaking | 110 Hz   | 1.13 | -0.6 dB |
| Peaking | 223 Hz   | 0.47 | -5.0 dB |
| Peaking | 3465 Hz  | 1.26 | 7.0 dB  |
| Peaking | 14820 Hz | 4.2  | -5.3 dB |
| Peaking | 1478 Hz  | 3.37 | -1.4 dB |
| Peaking | 2780 Hz  | 2.34 | 1.9 dB  |
| Peaking | 3329 Hz  | 2.62 | -2.0 dB |
| Peaking | 4632 Hz  | 4.93 | 1.7 dB  |
| Peaking | 6569 Hz  | 7.24 | -1.9 dB |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.4dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 31 Hz    | 1.41 | 1.3 dB  |
| Peaking | 62 Hz    | 1.41 | -1.1 dB |
| Peaking | 125 Hz   | 1.41 | -3.7 dB |
| Peaking | 250 Hz   | 1.41 | -4.6 dB |
| Peaking | 500 Hz   | 1.41 | -2.0 dB |
| Peaking | 1000 Hz  | 1.41 | -0.7 dB |
| Peaking | 2000 Hz  | 1.41 | 1.2 dB  |
| Peaking | 4000 Hz  | 1.41 | 6.9 dB  |
| Peaking | 8000 Hz  | 1.41 | -1.0 dB |
| Peaking | 16000 Hz | 1.41 | -2.3 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/NocturnaL%20Audio%20Atlantis/NocturnaL%20Audio%20Atlantis.png)