# Allen Mack

**Founder & System Architect — AI Infinity Force One**
Self-taught, building solo from Williston, Florida. I design and build zero-trust security systems in Rust — software that fails closed, keeps tamper-evident records, and can prove what it did.

**Available for hire** — freelance development, $50 minimum project. Reach me at a95674127@gmail.com or through my site below.

## Flagship work (proprietary — code private, available for licensing)

**AI Infinity Force One Vault — the MACK stack**
A Rust zero-trust security and verification platform. A 12-lane detection-containment pipeline routes every payload by risk score: clean work executes, suspicious work runs in Landlock-confined process isolation, and high-risk payloads are sealed in a forensic hold — if isolation is unavailable, the system rejects rather than downgrades. Persistent hash-chained ledger, sealed forensic records, REST API, and a full test suite (215 tests passing). An NSF SBIR project pitch for this platform was submitted in October 2026.

**VaultLane**
A local-first, zero-trust credential broker. Argon2id + XChaCha20-Poly1305 vault that serves secrets to child processes by least-privilege environment injection or over an authenticated local socket — with kernel armor, output redaction, a hash-chained audit log, and passphrase rotation. 66 tests passing.

**Autonomous Mack Stealth Core**
A sealed, named-entry keyring with a default-deny policy-as-code engine and a SHA-256 hash-chained audit log. 27 tests passing.

## Public work

**ATM Go — Cash Dash** — an original endless-runner game, playable in the browser:
https://a95674127-beep.github.io/ATM-go/

**Games & books** — six original games and five books, including *Lily Bird Lane*:
- My site: https://muse.ai/s/allen-mack-official-site-gxx6xzxz3bxdxokm
- My store: https://7335025021269.gumroad.com

**Smart-Flow (SF-ITES)** — an integrated thermal-extraction and pump-monitoring system for water infrastructure, currently in design and development: ESP32/Raspberry Pi sensor mesh, split-core CT sensors, flow and pressure telemetry.

## Tools I work in

Rust · Python · C/C++ · PyO3 — applied cryptography (Argon2id, XChaCha20-Poly1305, SHA-256 hash chains), Landlock process isolation, REST APIs, IoT/edge systems (ESP32, Raspberry Pi, LoRa/NB-IoT).

---

*All repositories not marked public are proprietary and shown here by description only. Licensing and project inquiries: a95674127@gmail.com*
