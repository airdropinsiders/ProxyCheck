# PROXY CHECKER

## Tools and components required
1. Nodepay Account| Register: [https://app.nodepay.ai/register](https://app.nodepay.ai/register?ref=2ef5JE5Tr7XfYUL)
2. Proxies Static Residental | [FREE 10 PREMIUM PROXIES](https://www.webshare.io/?referral_code=gbny3acbph42)
3. VPS (OPTIONAL) and Python3

# Setup 
- Install Python For Windows: [Python](https://www.python.org/ftp/python/3.13.0/python-3.13.0-amd64.exe)
- For Unix: ``apt install python3 python3-pip -y``
- Download this script: [ProXer](https://github.com/airdropinsiders/ProxyCheck/archive/refs/heads/main.zip) or ``git clone https://github.com/airdropinsiders/ProxyCheck``
- Open your Terminal/CMD and make sure you at ProXer directory
- Installing requirements:
>Windows
```bash
python -m pip install -r requirements.txt
```
>Unix
```bash
python3 -m pip install -r requirements.txt
```
# Run
- Run the script:
>Windows
```bash
python main.py
```
>Unix
```bash
python3 main.py
```
- Insert your proxies filename
>Supported Format
```bash
http://host:port
http://user:pass@host:port
socks4://host:port
socks4://user:pass@host:port
socks5://host:port
socks5://user:pass@host:port
```
- Proxies result will saved to folder named ``proxy_results``
- Good Proxies will saved to ``good-proxies.txt``
- Bad Proxies will saved to ``bad-proxies.txt``

# Credit
- https://github.com/im-hanzou/