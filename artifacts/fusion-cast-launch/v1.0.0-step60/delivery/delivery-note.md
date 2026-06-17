# Fusion Cast Commercial Delivery Note

Order: fusion-cast-launch
Created: 2026-06-14T18:02:57.142Z

Included:

- 1 main MP4
- 3 variant MP4 files
- proof frames and proof reports
- order source summary
- compiled Remotion manifests
- render and variant reports
- SHA256 asset hash manifest

Boundary:

- This is a non-sample commercial order package.
- Order inputs are approved for local release-gate validation.
- Visual QA, manual art-direction approval, multi-format output, audio, captions, and release gate remain separate checks until their reports pass.
- Do not claim commercial release readiness from this package unless release gate returns ok=true.

Step 45 aspect outputs:

- adaptive 16:9 / 9:16 / 1:1 deliverables are available when listed in `manifests/aspect-output-manifest.json`.
- 9:16 and 1:1 preserve the full 16:9 foreground frame; only the background fill is cropped and blurred.
- native vertical scene re-layout remains separate from this adaptive output proof.
