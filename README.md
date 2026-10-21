# Aura releases

This public repository hosts signed Aura catalog releases and distribution assets.

Each catalog release is tagged `catalog-YYYY-MM-DD` and contains `catalog-1.json` plus its detached Ed25519 signature `catalog-1.json.sig`. The Aura Core downloads the pair from the latest release and verifies it against the public key pinned in the platform.
