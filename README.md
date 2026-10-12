# mc-server-cost-model

A transparent worksheet for estimating a Minecraft fleet's monthly operating cost and capacity. Player slots are not capacity: use repeatable workload measurements and include failure headroom.

## Model
Inputs include proxy and game nodes, database/cache services, storage, backups, bandwidth, monitoring, and reserved capacity. Calculate a node-loss scenario before sizing production.

Replace sample prices with current provider quotes. `players-per-game-node` intentionally remains unset until measured on the actual plugin set and world. This repository makes no benchmark or capacity guarantee. MIT licensed.
