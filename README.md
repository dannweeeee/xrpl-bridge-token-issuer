# XRPL Bridge Token Issuer

Scripts to issue xrpl tokens in the xrpl bridge devnet.

## Setup

Install the xrpl package:

```sh
pip install xrpl-py
```

Activate the virtual environment: On macOS and Linux, run:

```sh
source myenv/bin/activate
```

On Windows, run:

```sh
.\myenv\Scripts\activate
```

Set config:

```json
{
  "node_url": "https://s.devnet.rippletest.net:51234",
  "currency_code": "SGD",
  "seed": "sEd7nEkquz3AKirhJBKvwYWswewygVh",
  "issue_quantity": 1000000,
  "faucet_host": "faucet.devnet.rippletest.net"
}
```

## Usage

```sh
python issuer.py
```
