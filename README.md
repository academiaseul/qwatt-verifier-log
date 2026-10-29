# qwatt-verifier-log

Decisions published by the QWATT independent verifier host, from public data only. `decisions.jsonl` (every batch signed or refused, with the evidence commit it judged) and `refusals.jsonl` only grow; `status.json` is replaced, at most every 5 minutes. Written only by that host's deploy key. One directory per run.

Check it with the code at [github.com/academiaseul/QWATT](https://github.com/academiaseul/QWATT):

```
node ops/evidence-audit.js <clone> --kind verifier-log
```

Simulated input · assurance A0 · Stellar testnet. QWATT is not electricity, not an investment, not a security, not a renewable energy certificate and not a carbon credit.
