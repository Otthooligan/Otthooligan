# Otthooligan
### Full-stack applications · Audio software · Developer tools

I work with **TypeScript, JavaScript, Python, and C++**, exploring how clear interfaces connect to reliable processing systems. My project work spans React applications, a DAW translation tool, audio plugin interfaces, and model-preparation tooling.

**Contact:** [messiahproduction81@gmail.com](mailto:messiahproduction81@gmail.com)

## Selected projects

### DAW Translation Tool
**React · TypeScript · Node.js · Express · Vitest**

A development-stage application for translating supported Ableton Live and FL Studio project data through a shared session model.

- Browser workflow for file upload, target selection, validation reports, and artifact downloads.
- Separate stages for parsing, routing, automation processing, optional gain adjustment, and output generation.
- Explicit reporting of preserved, approximated, unsupported, and skipped features.
- Regression tests and checksum-bound validation records.

**Status:** Implemented conversion paths with ongoing native-DAW validation. Not presented as lossless or production-certified conversion.

[Read the technical overview →](./projects/daw-translation.md)

### LILO Audio Tools
**JavaScript · HTML/CSS · C++ · JUCE · CMake · React/TypeScript in the separate mastering project**

Audio-processing interfaces connecting simple controls and detailed editing to native plugin processing.

- Simple macro controls and advanced module views.
- Interactive EQ editing, filter-response visualization, and native metering.
- Web-to-native parameter synchronization, host automation, and persistent state.
- Regression checks for control updates and EQ behavior.

**Status:** Development implementations. Browser previews, experimental features, and native processing have distinct validation boundaries.

[Read the technical overview →](./projects/lilo-audio-tools.md)

### EcoPlot / PLANT Group
**Python · LoRA/PEFT tooling · React/TypeScript and Capacitor application context**

My evidenced contribution centers on tooling for an offline-AI prototype: adapter conversion, model preparation, and response-checking scripts.

- Python utilities for converting MLX adapter weights to PEFT format.
- Model merging and GGUF preparation workflows.
- A verification harness for inspecting response length and missing-data behavior.

**Status:** Prototype tooling. The inspected mobile model provider and bridge remain placeholders; this is not a claim of shipped offline inference or sole authorship of EcoPlot.

[Read the contribution overview →](./projects/ecoplot.md)

### Helux Creator Workspace
**Next.js · React · TypeScript · Tailwind CSS**

A creator-tool prototype with React state providers, workspace/editor components, and server-side AI integration code, including request validation and cancellation handling.

**Status:** Prototype. Next.js experience here is separate from the React/Vite applications above.

## Technical focus

| Area | Technologies and practices |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, C++ |
| Web interfaces | React, HTML/CSS, Vite, Next.js prototypes, Tailwind CSS |
| Backend | Node.js, Express, REST APIs, structured data conversion |
| Testing and build | Git, Vitest, jsdom, CMake/CTest, GitHub Actions configuration |
| Audio | JUCE, DSP integration, EQ, dynamics, metering, host automation |
| AI tooling | Adapter conversion, model preparation, AI-assisted development with explicit review and validation |

## How I approach development

- Trace user actions through the interface, service boundary, processing, and output.
- Separate a working implementation from a mock, prototype, or planned integration.
- Use regression tests to capture behavior and failure cases.
- Keep provenance and limitations visible when transforming user data.
- Use AI assistance alongside code inspection and verification.

## About this portfolio

These are concise technical summaries, not public source releases. Project histories include collaborators and AI-assisted work; descriptions do not imply sole authorship. No private source code, credentials, customer data, or internal validation artifacts are included.

React with Capacitor is web technology packaged for mobile; it is not React Native. Cloud deployment, production usage, and performance metrics are omitted where they have not been established.

