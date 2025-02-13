# Peering (your own node)

### Important network info

<table data-header-hidden><thead><tr><th width="181"></th><th></th></tr></thead><tbody><tr><td>Info &#x26; Faucet</td><td><a href="https://hooks-testnet-v3.xrpl-labs.com">https://hooks-testnet-v3.xrpl-labs.com</a></td></tr><tr><td>Explorer</td><td><a href="https://hooks-testnet-v3-explorer.xrpl-labs.com/">https://hooks-testnet-v3-explorer.xrpl-labs.com/</a></td></tr><tr><td>Technical docs</td><td><a href="https://xrpl-hooks.readme.io/">https://xrpl-hooks.readme.io/</a></td></tr><tr><td>WebSocket URL</td><td>wss://hooks-testnet-v3.xrpl-labs.com</td></tr><tr><td>Public peering</td><td>Network ID: <code>21338</code><br>Peer 1: <code>159.65.199.56</code> Port: 21338<br>Peer 2: <code>139.59.98.59</code> Port: 21338<br>Peer 3: <code>88.99.3.241</code> Port: 21338<br>Peer 4: <code>88.99.4.45</code> Port: 21338</td></tr><tr><td>Binary &#x26; config</td><td>For ubuntu 22.04:<br><br>Download: <a href="https://hooksv3d.xrpl-labs.com/hooksv3d.tar">https://hooksv3d.xrpl-labs.com/hooksv3d.tar</a> <br><br>Extract, then run: <br><code>./hooksv3d --net --quorum=5 --conf hooksv3.cfg</code> Config file sample (to be saved as <code>hooksv3.cfg</code>): <a href="https://qsecdtj.dlvr.cloud/pasted_1.txt">https://qsecdtj.dlvr.cloud/pasted_1.txt</a> (edit the database path)</td></tr><tr><td>Validators</td><td><code>[validators] nHDs6fHVnhb4ZbSFWF2dTTPHoZ6Rr39i2UfLotzgf8FKUi7iZdxx nHUvgFxT8EGrXqQZ1rqMw67UtduefbaCHiVtVahk9RXDJP1g1mB4 nHU7Vn6co7xEFMBesV7qw7FXE8ucKrhVWQiYZB5oGyMhvqrnZrnJ nHBoJCE3wPgkTcrNPMHyTJFQ2t77EyCAqcBRspFCpL6JhwCm94VZ nHUVv4g47bFMySAZFUKVaXUYEmfiUExSoY4FzwXULNwJRzju4XnQ nHBvr8avSFTz4TFxZvvi4rEJZZtyqE3J6KAAcVWVtifsE7edPM7q nHUH3Z8TRU57zetHbEPr1ynyrJhxQCwrJvNjr4j1SMjYADyW1WWe nHBdSXv3DhYJVXUppMLpCwJWDFVQyFdZrbMxeh8CFiBEvfTCy3Uh nHUJbfgaAtkbuAdtrqCDerP99PcprcpyqakZTsYpkQdb67aKKyJn</code></td></tr><tr><td>UNL (VL)</td><td><a href="http://vl3.beta.bithomp.com/">vl3.beta.bithomp.com</a></td></tr></tbody></table>



### Connect Xumm to V3

<figure><img src="../.gitbook/assets/image.png" alt="" width="145"><figcaption></figcaption></figure>

To connect Xumm to the Hooks V3 staging net scan this QR with the QR scanner in Xumm to add the endpoint (above) to the Xumm node list.

### Network future

While the Hooks V3 staging net primarily exists to allow developers to test the Hooks amendment, the Hooks V3 staging net is feature complete: all amendments are enabled on this network & the network is publicly accessible (WebSocket, rippled peering).

While there is no indication at this point that there’s insufficient capacity to support Hooks & XLS20 testing, XRPL Labs will increase network capacity & more [network capacity](https://twitter.com/alloynetworks/status/1533867084928761857) has [been pledged](https://twitter.com/nbougalis/status/1533885609894465536) (and three parties operating the staging network is enough: this keeps it easy to roll out updates, fixes, etc.)
