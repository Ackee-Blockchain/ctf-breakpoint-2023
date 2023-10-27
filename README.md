# Run in Solana Playground
- Start local validator
    ```bash
    solana-test-validator
    ```
- Open the exploits directly in Solana Playground or alternatively import it from GitHub:
    - Exploit 0: [Playground](https://beta.solpg.io/653a6ffcfb53fa325bfd0c04), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit0)
    - Exploit 1: [Playground](https://beta.solpg.io/653a7023fb53fa325bfd0c05), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit1)
    - Exploit 2: [Playground](https://beta.solpg.io/653a7093fb53fa325bfd0c06), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit2)
    - Exploit 3: [Playground](https://beta.solpg.io/653b8742fb53fa325bfd0c09), [GitHub](https://github.com/Ackee-Blockchain/solpg-exploit3)

- ### Do not forget to change the cluster to localhost
    - Within the lower left corner settings


- Useful commands:
    ```bash
    solana airdrop 100
    ```
    ```bash
    build
    ```
    ```bash
    deploy
    ```
    ```bash
    test
    ```



# Run locally
- ### Prerequisites
    - solana-cli
        ```bash
        solana-install init 1.16.17
        ```
    - Anchor 0.28.0
        ```bash
        avm install 0.28.0 && avm use 0.28.0
        ```

- ### (if you did not setup the default wallet) Generate keypair:
    ```shell
    solana-keygen new # use the default path, as it is defined within Anchor.toml (~/.config/solana/id.json)
    ```

- ### Build and run the exploits
    ``` shell
    git clone https://github.com/Ackee-Blockchain/ctf-breakpoint-2023.git
    ```
    ``` shell
    cd ctf-breakpoint-2023
    ```
    ``` shell
    anchor build
    ```
    ``` shell
    yarn install
    ```
    ``` shell
    anchor run exploit<n> # replace <n> by the number of the exploit
    ```
