
‼️ THIS IS THE FORK WITH ADDING SNI VARIABLES

[Juicity is a quic-based proxy protocol and implementation, inspired by tuic (with many thanks)](https://github.com/juicity/juicity)

---------------------------------------------------------------------------------------------------------------------------------------------------------

#### I just add the SNI as a variable put your SNI during installation

#### ‼️ Installation

```
bash <(curl -fsSL https://raw.githubusercontent.com/opiran-club/juicity/main/juicity.sh --ipv4)
```

---------------------------------------------------------------------------------------------------------------------------------------------------------

### Android plugin

 - [Juicity-PLUGIN-for-Nekobox&Matsuri](https://github.com/MatsuriDayo/plugins/releases/tag/juicity-test-3)

---------------------------------------------------------------------------------------------------------------------------------------------------------
‼️
 - DO NOT FORGET TO PUT "ALLOW IN SECURE" ON "TRUE" ‼️

---------------------------------------------------------------------------------------------------------------------------------------------------------

## Client

- [juicity/juicity-client](cmd/client/README.md) <img src="https://www.v2fly.org/tools/win.svg" height=16/><img src="https://www.v2fly.org/tools/linux.svg" height=16/><img src="https://www.v2fly.org/tools/apple.svg" height=16/> (CLI)
- [daeuniverse/dae](https://github.com/daeuniverse/dae) <img src="https://www.v2fly.org/tools/linux.svg" height=16/> (CLI)
- [daeuniverse/daed](https://github.com/daeuniverse/daed) <img src="https://www.v2fly.org/tools/linux.svg" height=16/> (Web UI)
- [v2rayA/v2rayA](https://github.com/v2rayA/v2rayA) <img src="https://www.v2fly.org/tools/win.svg" height=16/><img src="https://www.v2fly.org/tools/linux.svg" height=16/><img src="https://www.v2fly.org/tools/apple.svg" height=16/> (Web UI)

---------------------------------------------------------------------------------------------------------------------------------------------------------

### Link Format

Full parameters:
```
juicity://uuid:password@122.12.31.66:port?congestion_control=bbr&sni=www.example.com&allow_insecure=0&pinned_certchain_sha256=CERT_HASH
```
Mini parameters:
```
juicity://uuid:password@example.com:port?congestion_control=bbr
```
