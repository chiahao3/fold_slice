# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v0.0.1] - 2024-12-11
### Added
- Add error metric of `ptyrad` to the `GPU_MS` engine emulate the NRMSE calculation. Note that this error value has no effect to the optimization behavior and it's behaving like the L1 (Gaussian).
### Changed
- Change error calculation to all iteration temporarily for benchmark purpose. This will double the needed time for forward pass so don't take the iteration time to seriously.
