# T-Rex Miner

**Fastest NVIDIA GPU miner**  
Leading performance on KawPow • Ethash • Autolykos2 • Octopus • FishHash • HeavyHash

T-Rex Miner – the ultimate high-speed NVIDIA miner. №1 hashrate on Ravencoin, Ergo, Kaspa, Iron Fish, Conflux, Alephium, Karlsen and others. Supports KawPow, Autolykos2, HeavyHash, FishHash, Octopus, Blake3, KarlsenHashv2, Ethash, ProgPoW variants. Complete LHR bypass (100% unlock), dual/triple intensity mining, core/memory/power/fan overclocking, HTTP+JSON monitoring API, automatic restart on crash. Only 1% developer fee. Best choice for RTX 40/30/20 series and older cards.




## Supported Algorithms (1% dev fee)

| Algorithm         | Example coins                  |
|-------------------|--------------------------------|
| ethash            | Ethereum Classic, EthereumPoW, Larissa |
| etchash           | Ethereum Classic (post-2025)   |
| kawpow            | Ravencoin, Neoxa, Clore        |
| autolykos2        | Ergo                           |
| octopus           | Conflux                        |
| fishhash          | Iron Fish                      |
| heavyhash         | Kaspa                          |
| karlsenhashv2     | Karlsen                        |
| blake3            | Alephium                       |
| sha512_256d       | Radiant                        |
| nexus             | Nexus                          |
| mtp               | Firo (legacy)                  |
| progpow variants  | Veil, Sero, Zano               |

All algorithms — 1% dev fee · 60-second mining sessions

## Features
- Highest hashrate on KawPow, Autolykos2, FishHash, Octopus
- Full LHR unlock (100% on supported algorithms)
- Dual & triple mining support (e.g. Ergo + Kaspa + Alephium)
- Built-in overclocking (core/memory/power/fan)
- Web monitoring dashboard + JSON-API
- Watchdog with automatic restart
- Ultra-low stale & reject shares
- HiveOS / RaveOS / minerstat / SimpleMining ready

## GPU Support
All NVIDIA GPUs from GTX 900 series and newer  
RTX 40xx • 30xx • 20xx • 16xx • GTX 10xx • Titan series

## Quick Start Examples

**Windows (.bat)**
```bat
t-rex.exe -a kawpow -o stratum+tcp://rvn.2miners.com:6060 -u YOUR_RAVEN_WALLET.RIG001 -p x
