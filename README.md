# CyberDefend: Packet Wars

An interactive 2D cybersecurity network defense game built in pure HTML5 Canvas and vanilla JavaScript with synthesized Web Audio API sound effects.

---

## 1. Overview & Game Mechanics
Players take on the role of a Network Security Engineer defending the Core Database Server from four classes of escalating automated cyber threats:
- **Port Scanners**: Fast reconnaissance probes.
- **Brute-Force Bots**: Armored botnet agents spraying passwords.
- **Phishing Payloads**: High-speed credential lures.
- **Adversarial Exploits**: High-durability boss payloads designed to evade simple defenses.

### Defensive Countermeasures (Towers)
1. **Firewall Filter (50⚡)**: Rapid single-target packet inspection laser.
2. **Rate Limiter Node (80⚡)**: Wide AoE pulse wave that suppresses botnet swarms.
3. **AI Inspector Node (120⚡)**: High-damage neural burst targeting phishing payloads.
4. **Quantum Honeypot (150⚡)**: Extreme damage countermeasure to stall adversarial exploit waves.

---

## 2. Technical Architecture
- **Vanilla Game Loop**: Driven by `requestAnimationFrame` with delta-time motion and state machine (`START`, `RUNNING`, `GAME_OVER`).
- **Mathematical Collision Detection**: Custom point-to-segment distance algorithm ensuring towers cannot be placed directly on the network packet pipeline.
- **Web Audio API Synthesizer**: Pure programmatic sound synthesis (zero external audio file dependencies).
- **Particle System**: Real-time particle burst engine for hit confirmations and packet neutralization.

---

## 3. How to Play
Open `index.html` in any modern web browser or play it directly on the live portfolio at [https://ariya-boop.github.io](https://ariya-boop.github.io).
