# Turtle Beach Elite Pro 2 SuperAmp
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.2dB
GraphicEQ: 21 -3.6; 23 -3.6; 25 -3.7; 28 -3.7; 31 -3.8; 34 -3.7; 37 -3.6; 41 -3.5; 45 -3.4; 49 -3.4; 54 -3.3; 60 -3.4; 66 -3.5; 72 -3.7; 79 -3.8; 87 -4.0; 96 -4.1; 106 -4.1; 116 -4.1; 128 -4.2; 141 -4.4; 155 -4.5; 170 -4.5; 187 -4.3; 206 -3.4; 227 -2.4; 249 -1.1; 274 0.9; 302 0.7; 332 1.8; 365 4.2; 402 4.0; 442 1.6; 486 -0.8; 535 -2.6; 588 -3.4; 647 -2.8; 712 -1.0; 783 0.2; 861 0.9; 947 0.6; 1042 -0.3; 1146 -0.7; 1261 -1.0; 1387 -1.1; 1526 -0.9; 1678 -1.0; 1846 -1.2; 2031 -1.3; 2234 -0.9; 2457 0.6; 2703 0.6; 2973 0.7; 3270 0.5; 3597 -1.1; 3957 -2.8; 4353 -1.2; 4788 2.4; 5267 5.8; 5793 4.8; 6373 2.0; 7010 0.9; 7711 -3.7; 8482 -8.6; 9330 -7.6; 10263 -3.0; 11289 -2.7; 12418 -4.5; 13660 -2.8; 15026 -0.0; 16529 0.0; 18182 -1.4; 20000 -4.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Turtle Beach Elite Pro 2 SuperAmp GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Turtle Beach Elite Pro 2 SuperAmp ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 24 Hz    | 0.84 | -2.9 dB |
| Peaking | 182 Hz   | 0.29 | -4.6 dB |
| Peaking | 358 Hz   | 2.08 | 8.0 dB  |
| Peaking | 5610 Hz  | 3.94 | 7.4 dB  |
| Peaking | 8899 Hz  | 2.64 | -9.2 dB |
| Peaking | 412 Hz   | 6.29 | 1.6 dB  |
| Peaking | 591 Hz   | 3.02 | -3.0 dB |
| Peaking | 844 Hz   | 2.55 | 2.8 dB  |
| Peaking | 1610 Hz  | 1.42 | -0.7 dB |
| Peaking | 19949 Hz | 1.95 | -4.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Turtle%20Beach%20Elite%20Pro%202%20SuperAmp/Turtle%20Beach%20Elite%20Pro%202%20SuperAmp.png)