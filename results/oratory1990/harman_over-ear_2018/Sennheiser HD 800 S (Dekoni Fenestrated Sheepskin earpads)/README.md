# Sennheiser HD 800 S (Dekoni Fenestrated Sheepskin earpads)
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 5.9; 60 5.4; 66 4.9; 72 4.5; 79 3.9; 87 3.4; 96 2.9; 106 2.4; 116 1.9; 128 1.4; 141 0.9; 155 0.6; 170 0.2; 187 -0.0; 206 -0.3; 227 -0.4; 249 -0.5; 274 -0.4; 302 -0.3; 332 -0.2; 365 -0.1; 402 -0.1; 442 -0.1; 486 -0.1; 535 -0.1; 588 -0.1; 647 -0.1; 712 -0.1; 783 -0.2; 861 -0.2; 947 -0.1; 1042 0.2; 1146 0.4; 1261 1.0; 1387 2.0; 1526 2.9; 1678 3.8; 1846 4.2; 2031 4.1; 2234 3.5; 2457 2.1; 2703 0.1; 2973 -0.5; 3270 0.3; 3597 1.7; 3957 1.5; 4353 -0.9; 4788 -2.9; 5267 -1.3; 5793 -1.2; 6373 -3.2; 7010 -2.7; 7711 -2.6; 8482 -1.7; 9330 0.0; 10263 -1.2; 11289 -6.7; 12418 -7.1; 13660 -4.6; 15026 -6.1; 16529 -10.2; 18182 -11.6; 20000 -10.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 800 S (Dekoni Fenestrated Sheepskin earpads) GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 800 S (Dekoni Fenestrated Sheepskin earpads) ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.9dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 36 Hz    | 0.57 | 6.7 dB  |
| Peaking | 1884 Hz  | 2.22 | 4.7 dB  |
| Peaking | 6556 Hz  | 4.65 | -2.5 dB |
| Peaking | 17755 Hz | 0.47 | -4.2 dB |
| Peaking | 18942 Hz | 0.72 | -8.0 dB |
| Peaking | 2914 Hz  | 6.53 | -1.7 dB |
| Peaking | 3774 Hz  | 4.66 | 2.3 dB  |
| Peaking | 4742 Hz  | 7.21 | -2.9 dB |
| Peaking | 9808 Hz  | 4.86 | 3.5 dB  |
| Peaking | 11758 Hz | 5.84 | -4.6 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/Sennheiser%20HD%20800%20S%20(Dekoni%20Fenestrated%20Sheepskin%20earpads)/Sennheiser%20HD%20800%20S%20(Dekoni%20Fenestrated%20Sheepskin%20earpads).png)