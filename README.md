# FormAI Live — Project Portfolio

**Computer Vision · Exercise Analysis · JavaScript · MediaPipe**

> Public project case study. **The application source repository is private** and is not included here.

[View the portfolio website (after GitHub Pages is enabled)](https://fernandatrevi.github.io/formai-portfolio/) · [FormAI application (deployment link; availability not verified)](https://formai-live.onrender.com/) · [Technical case study](docs/CASE_STUDY.md)

## What is FormAI Live?

FormAI Live is an experimental browser-based application for reviewing exercise videos with pose estimation. It samples video frames, detects body landmarks with MediaPipe and computes approximate **2D joint angles** to generate exploratory, exercise-specific observations.

The prototype explores squats, deadlifts, lunges and biceps curls. It **does not diagnose injuries, guarantee safe technique, or replace a qualified coach or clinician**.

## Technical highlights

- **Computer vision:** MediaPipe Pose Landmarker, landmark-visibility checks and approximate joint-angle calculations.
- **Frontend:** JavaScript (ES modules), HTML5, CSS3 and Vite.
- **User accounts:** Supabase Auth for authentication and account recovery.
- **Engineering workflow:** source control, automated tests and CI checks.
- **Privacy:** source code stays in a separate private repository; this public showcase includes original explanatory materials only.

## Project workflow

```text
User selects exercise → Uploads video → Frame sampling
→ Pose landmark detection → Visibility checks
→ 2D joint-angle estimates → Exploratory observations
```

## Project documentation

- [Technical case study](docs/CASE_STUDY.md)
- [Architecture and data flow](docs/ARCHITECTURE.md)
- [Interview talking points](docs/INTERVIEW.md)
- [Public portfolio landing page](index.html)

## Limitations

Results depend on lighting, clothing, camera orientation, image quality and visible joints. Two-dimensional video analysis is not a complete biomechanical assessment. Rules and alerts have **not** been clinically or professionally validated.

## For recruiters

The full source code is private. I can discuss engineering decisions, demonstrate the experience when deployment is available, and explain constraints, testing and possible next steps. This repository intentionally does **not** contain the application code.

**Author:** Fernanda Treviño · Engineering student · Data Analytics, AI and software projects.
