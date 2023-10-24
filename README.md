# Run in Solana Playground
- Start local validator
    - `solana-test-validator`
- Open the exploits directly in Solana Playground or alternatively import it from GitHub:
    - Exploit 0: [Playground](https://beta.solpg.io/651aa5b1fb53fa325bfd0bce), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit0)
    - Exploit 1: [Playground](https://beta.solpg.io/651aab38fb53fa325bfd0bcf), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit1)
    - Exploit 2: [Playground](https://beta.solpg.io/651aac76fb53fa325bfd0bd2), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit2)
    - Exploit 3: [Playground](https://beta.solpg.io/651aab79fb53fa325bfd0bd0), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit3)


# Run locally
- ### Prerequisites
    - solana-cli
        - `solana-install init 1.16.17`
    - Anchor 0.28.0
        - `avm install 0.28.0 && avm use 0.28.0`

- ### (Optional) Generate keypair:
    - `solana-keygen new`

- ### Build and run the exploits
    - `git clone https://github.com/Ackee-Blockchain/ctf-breakpoint-2023.git`
    - `cd ctf-breakpoint-2023`
    - `anchor build`
    - `yarn install`
    - `anchor run exploit<n> # replace <n> by the number of the exploit`
