# EcoPlot / PLANT Group — Model Preparation Contribution

**Contribution focus:** Python tooling for an offline-AI prototype.

## Application context

EcoPlot is a land-management application using React, TypeScript, Capacitor, and Supabase. Its existing application includes mapping and environmental-data workflows. That broader architecture is context, not a claim that I authored the entire product.

## Evidenced contribution

- Adapter conversion utilities that map MLX LoRA tensor names and layouts to PEFT format.
- Model merging and GGUF preparation workflows.
- A response-inspection harness checking output length and missing-data behavior.

## Current boundaries

The inspected mobile provider and native bridge remain placeholders. The verification harness contains warning-based checks and does not establish a robust automated acceptance gate. The project should therefore be described as model-preparation tooling and an offline-inference prototype, not shipped offline AI.

Capacitor packages the React web interface for mobile; this is not React Native experience.

[Back to portfolio](../README.md)

