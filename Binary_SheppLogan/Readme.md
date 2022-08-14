# Shepp-Logan phantom image
```
Image type: Binary
Image size: 15 by 15
ROI: 13 by 13
Total qubit numbers: 169
```

## Team members
```
Theory researcher: Kyungtaek Jun: ktfriends@gmail.com
Computational researcher: Hyunju Lee: hyunjulee0824@gmail.com
```

### Optimization
```
1. Undetermined CT image with qubit variable
2. Calculate undetermined sinogram by Radon transform the CT image
3. Optimizing the undetermined sinogram to a sinogram of Shepp-Logan phantom images
```

#### Results
```
The lowest energy: -8273.12

1. QPU solver: Advantage_system6.1
Trial: 50 times with 10,000 shots for each time
Average: -7698.44

2. Hybrid solver: hybrid_binary_quadratic_model_version2p
Trial: 50 times (hybrid sover shows one local minimum energy only)
Average: -8273.12
```
