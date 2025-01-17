---
title: "Getting Started"
slug: "getting-started"
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Getting Started

To kickstart your journey as a developer in the Aptos ecosystem, set up your development environment as described in this section.

## Clone the Aptos-core repo

Start by cloning the `aptos-core` GitHub repo from [GitHub](https://github.com/aptos-labs/aptos-core).

1. Clone the Aptos repo.

      ```
      git clone https://github.com/aptos-labs/aptos-core.git
      ```

2. `cd` into `aptos-core` directory.

    ```
    cd aptos-core
    ```

3. Run the `scripts/dev_setup.sh` Bash script as shown below. This will prepare your developer environment.

    ```
    ./scripts/dev_setup.sh
    ```

4. Update your current shell environment.

    ```
    source ~/.cargo/env
    ```
5. Skip this below step if you are not installing an Aptos node.

    <Tabs groupId="network">
    <TabItem value="devnet" label="Devnet">

    Checkout the `devnet` branch using:

    ```
    git checkout --track origin/devnet
    ```
    </TabItem>
    <TabItem value="testnet" label="Testnet" default>

    Checkout the `testnet` branch using:

    ```
    git checkout --track origin/testnet-stable
    ```
    </TabItem>
    </Tabs>

## Install the CLI

Install the Aptos CLI following the [Installing Aptos CLI](/cli-tools/aptos-cli-tool/install-aptos-cli.md) guide. 

Now your basic Aptos development environment is ready.
