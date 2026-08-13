### gm

independent security researcher focused on cross-chain infrastructure.

i spend most of my time staring at bridge contracts, multisig configurations, and proxy upgrade patterns. if you're building a bridge and want another pair of eyes, DMs open.

#### currently poking at

- bridge message verification — DVN/validator trust assumptions
- multisig opsec — threshold analysis, key management gaps
- proxy upgrades — timelock bypass, implementation takeover vectors
- evm storage forensics — slot mapping, delegatecall context tracing

#### builds

| | |
|---|---|
| [bridge-security-toolkit](https://github.com/0xrivet/bridge-security-toolkit) | cross-chain bridge security analysis — DVN checks, timelock detection, admin key tracing |
| [evm-calldata-decoder](https://github.com/0xrivet/evm-calldata-decoder) | calldata & trace decoder — delegatecall resolution, Safe tx analysis |
| [onchain-monitor](https://github.com/0xrivet/onchain-monitor) | real-time on-chain event monitor — upgrades, ownership changes, multisig mods |
| [shadow-admin](https://github.com/0xrivet/shadow-admin) | discover hidden admin paths — roles, modules, unrevoked permissions |
| [storage-archaeologist](https://github.com/0xrivet/storage-archaeologist) | reconstruct storage history — binary search for when values changed |
| [solidity-audit-notes](https://github.com/0xrivet/solidity-audit-notes) | vulnerability patterns with working Foundry PoCs |

more at [0xrivet.xyz/tools](https://0xrivet.xyz/tools).

---

*the bridge is only as secure as its weakest validator*

<sub>pgp: coming soon</sub>
