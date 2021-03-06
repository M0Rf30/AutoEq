# Read Heath Audio MA600
See [usage instructions](https://github.com/jaakkopasanen/AutoEq#usage) for more options.

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.4dB
GraphicEQ: 21 -10.4; 23 -10.5; 25 -10.6; 28 -10.7; 31 -10.8; 34 -10.9; 37 -11.0; 41 -11.1; 45 -11.2; 49 -11.3; 54 -11.4; 60 -11.6; 66 -11.8; 72 -12.0; 79 -12.2; 87 -12.4; 96 -12.6; 106 -12.6; 116 -12.5; 128 -12.5; 141 -12.5; 155 -12.3; 170 -12.0; 187 -11.6; 206 -11.3; 227 -10.7; 249 -10.1; 274 -9.6; 302 -8.9; 332 -8.3; 365 -7.5; 402 -6.8; 442 -5.9; 486 -5.2; 535 -4.3; 588 -3.3; 647 -2.5; 712 -1.8; 783 -1.0; 861 -0.6; 947 -0.2; 1042 0.1; 1146 0.5; 1261 0.7; 1387 0.5; 1526 1.5; 1678 1.5; 1846 0.9; 2031 -0.4; 2234 -1.2; 2457 -0.7; 2703 -0.6; 2973 -0.9; 3270 -1.8; 3597 -3.3; 3957 -5.1; 4353 -8.5; 4788 -11.8; 5267 -9.5; 5793 -3.6; 6373 0.6; 7010 2.1; 7711 0.3; 8482 0.0; 9330 -0.1; 10263 -3.3; 11289 -3.3; 12418 -0.7; 13660 -4.4; 15026 -9.1; 16529 -7.2; 18182 -3.0; 20000 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Read Heath Audio MA600 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-23**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Read Heath Audio MA600 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-1.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **--0.4dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 33 Hz    | 0.22 | -10.3 dB |
| Peaking | 155 Hz   | 0.68 | -6.6 dB  |
| Peaking | 335 Hz   | 1.26 | -3.8 dB  |
| Peaking | 4772 Hz  | 4.04 | -12.7 dB |
| Peaking | 15580 Hz | 2.11 | -9.8 dB  |
| Peaking | 1436 Hz  | 0.85 | 4.3 dB   |
| Peaking | 1730 Hz  | 0.43 | -2.7 dB  |
| Peaking | 5437 Hz  | 6.84 | -3.6 dB  |
| Peaking | 6620 Hz  | 2.21 | 4.2 dB   |
| Peaking | 10654 Hz | 8.4  | -3.4 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Read%20Heath%20Audio%20MA600/Read%20Heath%20Audio%20MA600.png)