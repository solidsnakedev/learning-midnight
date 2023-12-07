```mermaid
flowchart LR
    A((Compact compiler))
    A --> B1[Contract \n Typescript/Javascript API]
    A --> B2[Zkir \n Circuits Intermediate Representation]
    A --> B3[Keys \n Circuits Prover and Verifier Keys]
```


```mermaid
flowchart TB
    A((Compact Contracts))
    A -->|Witness \n Functions| B[Private \n States]
    A -->|Public Operations \n Circuits| C[Public States \n Ledger]
```
