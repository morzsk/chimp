# chimp

CLI that takes voice sample(s) of a person and slices video into clips of that person speaking.

## Usage

> **Note:** interface is not yet implemented, the following is a mock.

```
chimp --samples <file>... --tolerance <0.0-1.0> --input <file> --output <dir>
```

- `--samples` — one or more reference audio or video files of the target speaker
- `--tolerance` — clip tightness; lower = clips cut closer to speech boundaries, higher = more padding
- `--input` — video file to extract clips from
- `--output` — directory to write clips into

## Assumptions

- Audio track is clean (no background noise, music, or significant degradation)
- Consistent recording environment across samples and input
