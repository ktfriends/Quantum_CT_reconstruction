# Quantum Supremacy in Tomographic Imaging: Advances in Quantum Tomography Algorithms
```
Paper: https://arxiv.org/abs/2502.04830
```

## Quantum Supremacy
```
1. Resistance to ring artifacts: horizontal error in the sinogram
2. Resistance to noisy projections: vertical error in the sinogram
3. Reduction in Required Projection Angles: limited angle (90 degree) in the sinogram
```

### File Description (Shepp-Logan image sample)
```
Figure 5: Quantum_supremacy(Shepp_Logan_50x50-Limited angles)
Figure 6: quantum supremacy(Body CT image 50x50 - ring artifacts)
Figure 8: quantum supremacy(Body CT image 50x50 - limited_angles)
```

## Reproducibility patch
- Config: `config.yaml` (or `configs/config.yaml` if you placed it there)
- Patch notebook: `./patch_code.ipynb`
- Dependency: `pyyaml` (`pip install pyyaml`)

### Purpose
- **Ring artifacts (ROW-based)**  
  Replace the “sinogram with errors” plotting cell in  
  `quantum supremacy(Body CT image 50x50 - ring artifacts).ipynb`  
  with the ROW-based block from `patch_code.ipynb`.  
  It uses `ring_rows` and `artifact_strengths` from the config, no randomness.

- **Limited angles (COLUMN-based)**  
  Replace the same cell in  
  `quantum supremacy(Body CT image 50x50 - limited_angles).ipynb`  
  with the COLUMN-based block. It zeros `missing_projection_columns`.

### How to run
1. Open the target notebook.
2. Ensure `config.yaml` is present at the path used in the code.
3. Select a `CASE` defined in the config.
4. Run the corresponding block from `patch_code.ipynb`.
5. Proceed with the rest of the notebook. No D-Wave token is required for these steps.
