## Deblock 

Simple deblocking filter by Manao and Fizick. It does a deblocking of the picture, using the deblocking filter of h264.

### Usage
```
Deblock (clip, quant=25, aOffset=0, bOffset=0)
```
* *quant* - the higher the quant, the stronger the deblocking. It can range from 0 to 60.
* *aOffset* - quant modifier to the blocking detector threshold. Setting it higher means than more edges will deblocked.
* *bOffset* - another quant modifier, for block detecting and for deblocking's strength. There again, the higher, the stronger.
