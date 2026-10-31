# NCT Device Catalogue

Official-source device identity catalogue for Hanwha/Samsung and Hikvision.
Only public model/manufacturer/type/source information belongs here. Never add device observations, customer/site data, credentials, signing private keys or diagnostic sessions.

## Publication

Reviewed catalogue payloads are signed by the maintainer outside this repository. Publish the signed catalogue and signed index over HTTPS. NCT verifies the pinned public key, checksum, schema and version before applying an update. Manufacturer collection produces review candidates, never automatically trusted releases.

Catalogue Endpoint: https://raw.githubusercontent.com/anoraq1/nct-device-catalogue/main/index.json
