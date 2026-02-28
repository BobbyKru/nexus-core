# Technical Specification (draft)

## Core
- Form: square, metal case (titanium / Nitinol)
- Size: ~90x90mm (tentative)
- Power: supercapacitor + minimal cell (hours, not days)
- Components: SoC + Secure Enclave + hardware encryption
- Interface: custom 24-pin connector + cryptographic handshake

## Shells
- Authentication: each shell has a signed certificate
- Activation: only after successful handshake with core
- Types: slider, keyboard, battery, projector, camera module

## Security
- No shell works without core authentication
- Keys stored in tamper-resistant hardware
- No backdoors, no cloud requirement
