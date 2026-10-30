# PokemonDB — Mobile Viewer

Encrypted client-side progressive web viewer for PokemonDB card collections.

## Architecture
- Valuations and collections are encrypted at rest with AES-256-GCM.
- Zero plaintext collection data is stored on remote servers.
- Decrypted entirely in-browser using the Web Crypto API via PIN authorization.
