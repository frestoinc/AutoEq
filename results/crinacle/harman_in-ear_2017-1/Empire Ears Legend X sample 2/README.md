# Empire Ears Legend X sample 2
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options and info.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
GraphicEQ: 21 -14.8; 23 -14.8; 25 -14.8; 28 -14.7; 31 -14.6; 34 -14.5; 37 -14.4; 41 -14.3; 45 -14.2; 49 -14.1; 54 -13.9; 60 -13.8; 66 -13.6; 72 -13.5; 79 -13.5; 87 -13.3; 96 -13.3; 106 -13.2; 116 -13.0; 128 -12.8; 141 -12.6; 155 -12.3; 170 -11.9; 187 -11.5; 206 -11.1; 227 -10.6; 249 -10.2; 274 -9.7; 302 -9.2; 332 -8.5; 365 -8.0; 402 -7.5; 442 -7.0; 486 -6.6; 535 -6.2; 588 -5.7; 647 -5.2; 712 -4.8; 783 -4.4; 861 -4.2; 947 -4.6; 1042 -5.4; 1146 -6.4; 1261 -7.3; 1387 -7.8; 1526 -8.1; 1678 -8.0; 1846 -7.8; 2031 -7.1; 2234 -6.0; 2457 -4.5; 2703 -3.2; 2973 -2.1; 3270 -1.1; 3597 -0.5; 3957 -0.5; 4353 -1.3; 4788 -0.5; 5267 -0.5; 5793 -2.1; 6373 -1.4; 7010 -4.0; 7711 -6.2; 8482 -7.1; 9330 -7.0; 10263 -6.5; 11289 -6.5; 12418 -6.5; 13660 -16.3; 15026 -26.5; 16529 -31.6; 18182 -30.9; 20000 -20.5
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Empire Ears Legend X sample 2 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Empire Ears Legend X sample 2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-4.2dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 22 Hz    | 0.28 | -8.0 dB  |
| Peaking | 143 Hz   | 0.58 | -4.1 dB  |
| Peaking | 726 Hz   | 2.75 | 2.4 dB   |
| Peaking | 8614 Hz  | 0.38 | 12.8 dB  |
| Peaking | 17106 Hz | 0.57 | -32.7 dB |
| Peaking | 1799 Hz  | 1.08 | -8.1 dB  |
| Peaking | 2462 Hz  | 0.44 | 5.1 dB   |
| Peaking | 8214 Hz  | 2.2  | -5.1 dB  |
| Peaking | 12530 Hz | 2.65 | 8.0 dB   |
| Peaking | 14685 Hz | 2.51 | -6.9 dB  |

### Fixed Band EQs
In case of using fixed band (also called graphic) equalizer, apply preamp of **-7.8dB** and set
gains manually with these parameters.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 31 Hz    | 1.41 | -8.6 dB  |
| Peaking | 62 Hz    | 1.41 | -5.1 dB  |
| Peaking | 125 Hz   | 1.41 | -5.2 dB  |
| Peaking | 250 Hz   | 1.41 | -3.1 dB  |
| Peaking | 500 Hz   | 1.41 | 1.0 dB   |
| Peaking | 1000 Hz  | 1.41 | 1.4 dB   |
| Peaking | 2000 Hz  | 1.41 | -2.4 dB  |
| Peaking | 4000 Hz  | 1.41 | 7.8 dB   |
| Peaking | 8000 Hz  | 1.41 | 6.3 dB   |
| Peaking | 16000 Hz | 1.41 | -29.7 dB |

### Impulse Response
In case of using Viper4Android or other convolution engine select WAV file with correct sampling frequency.

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/crinacle/harman_in-ear_2017-1/Empire%20Ears%20Legend%20X%20sample%202/Empire%20Ears%20Legend%20X%20sample%202.png)