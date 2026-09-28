# LILO Audio Tools

**Stack:** JavaScript, HTML/CSS, C++, JUCE, CMake. A separate mastering interface uses React and TypeScript.

## Purpose

Make audio processing approachable through simple controls while retaining detailed editing for advanced use.

## Interface and native integration

The channel strip pairs macro controls with advanced module views. Its interactive EQ interface provides frequency, gain, and filter-response visualization. The web interface is embedded in a JUCE plugin and communicates with native parameters, host automation, persistent state, and metering.

The channel strip itself uses plain JavaScript rather than React. React is used in the separate mastering project.

## Verification

Regression checks exercise parameter synchronization during dragging and expected EQ response properties. Native processing and build configuration provide a separate verification layer from browser interface checks.

## Current boundaries

Browser-only previews may use mock meter data. Experimental observer and pitch features are not represented as finished pitch-correction products. Build targets and implemented DSP do not by themselves establish a commercial release.

Project work includes existing dependencies, collaboration, and AI assistance. This summary does not claim original authorship of every algorithm or dependency.

[Back to portfolio](../README.md)

