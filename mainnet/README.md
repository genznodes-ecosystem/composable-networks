# Composable mainnet: centauri-1

## Hardware recommendation:
```
Quad core or larger amd64 CPU
64GB+ RAM
1TB+ NVMe Storage
```
## Binary:

Testnet-3 launch version: v2.3.5, precompiled binary for linux-amd64 could be found here: https://github.com/notional-labs/composable-centauri/releases/tag/v2.3.5

```
git clone https://github.com/notional-labs/composable-centauri
cd composable-centauri
git checkout v2.3.5
make install
```

## P2P connection:
You can set the peers/seeds in `config.toml`:
```
sed -i.bak -E "s|^(seeds[[:space:]]+=[[:space:]]+).*$|\1"'"c7f52f81ee1b1f7107fc78ca2de476c730e00be9@65.109.80.150:2635"'"|" ~/.banksy/config/config.toml
```

*Seeds:*
```
c7f52f81ee1b1f7107fc78ca2de476c730e00be9@65.109.80.150:2635
```

*Persistent peers:*
```
4cb008db9c8ae2eb5c751006b977d6910e990c5d@65.108.71.163:2630,63559b939442512ed82d2ded46d02ab1021ea29a@95.214.55.138:53656
```

## Explorer:
....
