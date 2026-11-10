# FormAI — Interview Guide

## 30-second pitch (English)

I built FormAI Live, an experimental web application for reviewing exercise videos using computer vision. It integrates MediaPipe Pose Landmarker in a JavaScript interface, estimates joint positions and approximate 2D angles, and presents exercise-specific observations. Beyond the computer vision, I worked on the end-to-end experience, account authentication, testing and documenting limitations. The source code is private, but this repository describes the architecture and design choices.

## Pitch de 30 segundos (español)

FormAI Live es una aplicación experimental que desarrollé para revisar videos de ejercicio mediante visión computacional. Integra MediaPipe para estimar puntos articulares, calcular ángulos aproximados en dos dimensiones y mostrar observaciones según el ejercicio. Además de la integración tecnológica, trabajé en la experiencia de usuario, autenticación, pruebas y documentación de limitaciones. El código está en un repositorio privado y este portafolio presenta las decisiones técnicas.

## Questions to prepare

**Did you train the AI model?** No. The prototype integrates a pretrained MediaPipe model. It should not be described as a custom-trained model.

**How do you know if feedback is correct?** The system includes landmark-visibility checks, but its rules are not clinically or professionally validated. A formal evaluation would need expert-annotated videos and accuracy measurements.

**Why keep the source private?** The application repository and history are not public. This portfolio openly documents the workflow, stack and limitations without providing repository access. Browser-delivered frontend code, however, can be inspected during a live demonstration.

**How is this relevant to a data analyst position?** The transferable skills are working with structured outputs, processing data, handling input-quality issues, communicating results and documenting assumptions. It does not replace direct experience with SQL, Power BI or Revenue Management.

**What would you improve next?** Rigorous evaluation datasets, testing across devices and conditions, accessible feedback and measurement of false positives and negatives.
