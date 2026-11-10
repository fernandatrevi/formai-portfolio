# FormAI Live | Technical Case Study

## Context and objective

FormAI Live is an experimental exercise-video review prototype developed as a technology and learning project. It investigates how off-the-shelf pose estimation can support understandable visual feedback without pretending to replace professional movement assessment.

## User flow

1. Select an exercise.
2. Review recommended video recording guidance.
3. Load a video in the browser.
4. Analyze sampled frames.
5. See estimated joint locations, approximate two-dimensional angles and exercise-specific observations.

## Implemented technology (according to the private project's documentation)

| Component | Technology | Function |
|---|---|---|
| Interface | HTML5, CSS3 | Responsive user experience |
| Runtime | JavaScript, Vite | Browser application and build |
| Pose estimation | MediaPipe Pose Landmarker | Detect estimated body landmark positions |
| Authentication | Supabase Auth | Sign-up, sign-in and password recovery |
| Engineering practices | GitHub Actions, Node.js tests | CI and automated checks |

## Why these choices?

Using a pretrained pose-estimation model avoids claiming that a custom machine-learning model has been trained. Landmark visibility checks attempt to avoid reporting measurements when required joints cannot be seen. Client-side video analysis can reduce the need to send uploaded videos to a proprietary backend, although the application may still fetch external libraries and models.

## What this portfolio demonstrates

- Transforming a user problem into a prototype with defined workflows.
- Working with computer-vision outputs and geometric calculations.
- Handling missing or uncertain input observations.
- Applying basic authentication, test and version-control practices.
- Explaining technical limitations and responsible-use boundaries.

## What it does NOT demonstrate

This project is not evidence of clinical accuracy, injury-prevention efficacy, production-grade security certification, proprietary model training or expertise in Snowflake, Alteryx or SQL. These would require separate projects and verification.

## Next validation steps

- Build a test set of diverse, consented recordings with expert annotations.
- Quantify landmark-visibility reliability and angle-estimation stability.
- Test different recording positions, lighting conditions and occlusions.
- Track false alarms and missed alerts, and refine user messaging.
- Add accessibility and mobile-browser compatibility testing.

## Interview-ready summary

> I developed an experimental web app that uses MediaPipe to detect body landmarks from exercise videos and transform landmark positions into understandable 2D measurements and observations. I focused on the end-to-end user experience, integration, input-quality checks, testing and communicating limitations. I kept the code private, but documented the design decisions and workflow in this public portfolio.

*The application source repository is private. This document is a case-study summary, not a reproduction of source code.*
