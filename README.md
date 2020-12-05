# Xiaomi Cloud Tokens Extractor
[![buymeacoffee_badge](https://img.shields.io/badge/Donate-buymeacoffe-ff813f?style=flat)](https://www.buymeacoffee.com/PiotrMachowski)

This tool/script retrieves tokens for all devices connected to Xiaomi cloud.

You will need to provide:
- username (e-mail or Xiaomi Cloud account ID)
- password
- Xiaomi's server region (`cn` - China, `de` - Germany etc.). Leave empty to check all available

In return all of your devices connected to account will be listed, together with their name, IP address and more.

## Other platforms

Install dependencies:
```bash
pip3 install pycryptodome pybase64 requests
```

Download and run script:
```bash
wget https://raw.githubusercontent.com/clemalex824/Xiaomi-cloud-tokens-extractor/master/token_extractor.py
python3 token_extractor.py
```


<a href="https://www.buymeacoffee.com/PiotrMachowski" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
