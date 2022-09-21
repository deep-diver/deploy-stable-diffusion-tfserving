# Stable Diffusion in TensorFlow Serving

This project explores and demonstrates how to deploy stable diffusion model with TensorFlow Serving. 

## To-do (step by step)

- [ ] one signature architecture
  - [ ] a signature to expose an endpoint, and make sure `text encoder`, `diffuser`, `decoder` models are called sequentially internally
  - [ ] enable GPU/TPU capability
  - [ ] enable dynamic batching capability
  
- [ ] multiple TensorFlow Serving
  - [ ] three TensorFlow Servings for `text encoder`, `diffuser`, and `decoder`
  - [ ] a central back-end server (or a client) to call each TensorFlow Servings sequentially
  - [ ] enable/disable GPU/TPU capability for each TensorFlow Serving
  - [ ] enable dynamic batching capability
  
- [ ] compare two different cases (TBD)
