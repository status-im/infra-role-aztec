# Description

This role deploys [Aztec Sequencer Node](https://docs.aztec.network/the_aztec_network/guides/run_nodes/how_to_run_sequencer) which is responsible for ordering transactions and producing blocks.

# Configuration

Required configuration includes:
```yaml
aztec_ethereum_hosts: ['http://localhost:8545/']
aztec_l1_consensus_host_urls: ['http://localhost:9200/']
aztec_attester_private_key:  '0x4321432143214321432143214321432143214321432143214321432143214321'
aztec_publisher_private_key: '0x4321432143214321432143214321432143214321432143214321432143214321'
aztec_fee_recipient_address: '0x1234123412341234123412341234123412341234'
aztec_coinbase_address:      '0x1234123412341234123412341234123412341234'
```
