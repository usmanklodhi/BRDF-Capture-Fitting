## Description (for wt_brdf.ipynb)

This repository contains a script implementing **Lambertian shading, Phong shading** and **neural rendering** techniques aimed at simulating realistic lighting effects and reflections. The script combines traditional Phong reflection modeling with neural network-based rendering to achieve advanced visual results. However, there are a few known issues that need to be addressed.

## Known Issues

1. **Incorrect Phong Implementation**  
   - The specular component in the current Phong model implementation does not respond accurately to parameter adjustments. This issue is likely due to an incorrect specular formula, which causes the specular highlights to remain unaffected by parameter changes.

2. **Neural Rendering Implementation Needs Debugging**  
   - The neural rendering functionality is not fully correct and may require further debugging. There might be inconsistencies in the neural network’s output or its integration within the rendering pipeline, leading to inaccuracies in the visual output.

---

Please refer to the code comments and structure for more information on the implementation.
