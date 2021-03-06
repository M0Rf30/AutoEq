# Audio-Technica ATH-ANC9
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.6dB
GraphicEQ: 21 -7.5; 23 -7.9; 25 -8.2; 28 -8.5; 31 -8.6; 34 -8.5; 37 -8.2; 41 -7.9; 45 -7.5; 49 -7.1; 54 -6.7; 60 -6.3; 66 -6.2; 72 -6.2; 79 -6.4; 87 -6.8; 96 -7.3; 106 -7.9; 116 -8.3; 128 -8.7; 141 -8.7; 155 -8.4; 170 -7.8; 187 -7.1; 206 -6.2; 227 -5.4; 249 -4.6; 274 -4.1; 302 -3.7; 332 -3.4; 365 -2.9; 402 -2.7; 442 -2.6; 486 -2.6; 535 -2.6; 588 -2.2; 647 -1.1; 712 0.6; 783 1.8; 861 2.5; 947 1.4; 1042 -1.1; 1146 -3.3; 1261 -5.0; 1387 -5.5; 1526 -5.6; 1678 -5.2; 1846 -5.2; 2031 -4.9; 2234 -4.7; 2457 -4.4; 2703 -4.9; 2973 -5.2; 3270 -5.4; 3597 -5.8; 3957 -7.6; 4353 -7.1; 4788 -8.9; 5267 -9.7; 5793 -9.1; 6373 -6.4; 7010 -5.7; 7711 -6.0; 8482 -4.0; 9330 -0.1; 10263 0.0; 11289 -3.2; 12418 -10.0; 13660 -12.2; 15026 -9.6; 16529 -6.6; 18182 -5.5; 20000 -3.6
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audio-Technica ATH-ANC9 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-25**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio-Technica ATH-ANC9 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **--0.8dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 29 Hz    | 0.64 | -8.1 dB  |
| Peaking | 144 Hz   | 0.75 | -7.7 dB  |
| Peaking | 1683 Hz  | 1.67 | -5.1 dB  |
| Peaking | 4941 Hz  | 1.28 | -8.9 dB  |
| Peaking | 14366 Hz | 1.73 | -12.0 dB |
| Peaking | 847 Hz   | 0.97 | -3.6 dB  |
| Peaking | 847 Hz   | 2.49 | 7.9 dB   |
| Peaking | 7817 Hz  | 5.15 | -2.3 dB  |
| Peaking | 9908 Hz  | 4.04 | 5.2 dB   |
| Peaking | 19031 Hz | 1.4  | -3.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Audio-Technica%20ATH-ANC9/Audio-Technica%20ATH-ANC9.png)