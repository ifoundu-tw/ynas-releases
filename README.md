# YNAS Releases

This public repository is the official binary update channel for YNAS.

- It contains signed version policy metadata and release packages only.
- YNAS verifies the Ed25519 policy signature and package SHA-256 before installation.
- Source code, NAS files, device identities, Firebase credentials, caches, and signing private keys are not published here.

Latest version metadata: [`version-policy.json`](version-policy.json)

YNAS is currently a personal preview. Install packages only on systems you trust and keep an independent backup of important files.

The Windows portable package includes its own Node.js, FFmpeg, and FFprobe runtime. Extract the complete ZIP, then open `YNAS 啟動.vbs`; no separate Node.js or FFmpeg installation is required.
