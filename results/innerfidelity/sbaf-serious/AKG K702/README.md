# AKG K702
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.8dB
GraphicEQ: 21 0.0; 23 1.8; 25 1.3; 28 0.6; 31 0.1; 34 -0.3; 37 -0.7; 41 -1.0; 45 -1.4; 49 -1.7; 54 -2.0; 60 -2.3; 66 -2.7; 72 -2.9; 79 -2.7; 87 -2.9; 96 -3.3; 106 -3.2; 116 -3.6; 128 -4.4; 141 -4.8; 155 -5.0; 170 -4.6; 187 -4.9; 206 -4.8; 227 -4.7; 249 -4.7; 274 -4.5; 302 -4.2; 332 -3.9; 365 -3.6; 402 -3.2; 442 -2.7; 486 -2.3; 535 -0.7; 588 0.2; 647 0.6; 712 1.1; 783 1.1; 861 0.6; 947 0.3; 1042 -0.3; 1146 -0.8; 1261 -0.6; 1387 -1.2; 1526 -2.3; 1678 -3.5; 1846 -4.0; 2031 -5.4; 2234 -5.5; 2457 -4.6; 2703 -2.9; 2973 -1.2; 3270 0.2; 3597 0.1; 3957 -0.9; 4353 -3.2; 4788 -3.5; 5267 -2.5; 5793 -4.0; 6373 -6.0; 7010 -6.5; 7711 -6.6; 8482 -7.0; 9330 -4.2; 10263 -0.1; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 -2.7; 18182 -5.4; 20000 -3.8
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`AKG K702 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-28**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `AKG K702 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **--0.1dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 176 Hz   | 0.6  | -5.2 dB |
| Peaking | 2118 Hz  | 2.65 | -5.8 dB |
| Peaking | 6647 Hz  | 2.31 | -5.9 dB |
| Peaking | 8432 Hz  | 5.17 | -5.3 dB |
| Peaking | 18627 Hz | 1.99 | -6.2 dB |
| Peaking | 20 Hz    | 2.63 | 2.8 dB  |
| Peaking | 744 Hz   | 2.93 | 2.4 dB  |
| Peaking | 3424 Hz  | 3.27 | 4.8 dB  |
| Peaking | 3769 Hz  | 1.64 | -3.2 dB |
| Peaking | 11911 Hz | 1.65 | 1.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/AKG%20K702/AKG%20K702.png)