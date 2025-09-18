# ssb_pointA_fix

Online calculator : https://dustinchen26.github.io/ssb_calculate/

## Usage
```
輸入可能有錯的 absFreqSsb 和 absFreqPointA ，和正確的 carrierBw ，
找出符合spec的組合

Instructions: Enter your desired frequencies (even if approximate) and carrier bandwidth. The algorithm will find the closest valid values according to 5G NR specifications.

absFreqSsb (kHz): 3563040 (Target SSB frequency)
absFreqPointA (kHz): 3554700 (Target Point A frequency)
carrierBw (RB): 273 (Resource blocks for carrier bandwidth)

Final Calculated Parameters:
gscn=7890, absFreqPointA=3554700, absArfcnPointA=636980, absFreqSsb=3563040, absArfcnSsb=637536, dlEarfcn=640256, nDlCenterFreq=3603840, Kssb=4, offsetToPointA=26

```
