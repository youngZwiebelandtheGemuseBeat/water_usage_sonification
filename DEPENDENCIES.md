# Dependencies

- **Pure Data Vanilla 0.57-0** is the reference version. The project’s patch load was checked on macOS on Apple Silicon using native ARM64. Other Pd versions and platforms are unverified.
- **`sigmund~`** ships with Pd Vanilla. The detector uses its `quality` outlet. The standard Pd installation includes it, so there are no additional Deken packages to install.
- **Microphone input** on channel 1 is required for live detection. The patch reads the configured sample rate at DSP startup and uses a local 2,048-sample block with 4× overlap for the FFT. Audio device and sample rate are set in Pd’s audio settings.

The main patch loads its modules through `[declare -path abstractions]`. This path is relative to `Wasserhahn.pd` and works without adding paths in Pd preferences. The prototype runs offline and needs no samples or datasets.

Download Pd from [Miller Puckette’s software page](https://msp.ucsd.edu/software.html). On Apple Silicon, use the native ARM64 slice of the macOS build.

If a future change requires a third-party external, record its name, version, architecture and purpose here. In Pd, use **Help → Find Externals** to find the matching package. On an Apple Silicon Mac, look for macOS ARM64 or universal builds.
