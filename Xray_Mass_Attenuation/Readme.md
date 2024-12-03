# Quantum Reconstruction and Segmentation Algorithm 
```
This quantum algorithm simultaneously performs CT image reconstruction and CT image setgmentation.
```

## Quantum Superposition State of Pixels
```
1. Superposition 1: I = a1*q1 + a2*q2 + --- + an*qn (I: superposed pixel, ai: X-ray mass attenuation coefficient)
2. Superposition 2: I = a1*q1 + (a2-a1)*q2 + --- + (an-a(n-1))*qn 
```

### File Description (Shepp-Logan image sample)
```
Xray_30by30_2MAC.ipynb: Sample size is 30 by 30 and has two X-ray mass attenuation coefficients.
Xray_30by30_3MAC.ipynb:Sample size is 30 by 30 and has three X-ray mass attenuation coefficients.
Xray_50by50_2MAC.ipynb: Sample size is 50 by 50 and has two X-ray mass attenuation coefficients.
Xray_50by50_3MAC.ipynb:Sample size is 50 by 50 and has three X-ray mass attenuation coefficients.
```
