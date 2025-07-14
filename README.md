# Free Proxy List

Welcome to our free proxy list\! This repository contains lists of free HTTP, HTTPS, SOCKS4, and SOCKS5 proxies. These lists are updated regularly to provide you with fresh proxies.


-----

## 🌎 Overview

This repository is dedicated to providing developers, researchers, and other users with easily accessible lists of public proxy servers. The proxies are categorized by protocol and are provided in simple `.txt` files for ease of use.

-----

## 📂 Repository Structure

The repository is organized as follows:

  * `http.txt`: A list of HTTP proxies.
  * `https.txt`: A list of HTTPS proxies.
  * `socks4.txt`: A list of SOCKS4 proxies.
  * `socks5.txt`: A list of SOCKS5 proxies.

-----

## 🚀 How to Use

You can use these proxy lists with a variety of tools and applications. Below are some examples of how to use the proxies with `wget` and `curl`.

### Using with `wget`

To use a proxy with `wget`, you can set the `http_proxy` or `https_proxy` environment variable.

**For HTTP Proxies**

```bash
export http_proxy='http://PROXY_IP:PROXY_PORT'
wget http://example.com
```

**For HTTPS Proxies**

```bash
export https_proxy='https://PROXY_IP:PROXY_PORT'
wget https://example.com
```

**For SOCKS Proxies**

`wget` does not directly support SOCKS proxies. You may need to use a tool like `proxychains` to use SOCKS proxies with `wget`.

### Using with `curl`

`curl` supports various proxy protocols.

**For HTTP Proxies**

```bash
curl -x http://PROXY_IP:PROXY_PORT http://example.com
```

**For HTTPS Proxies**

```bash
curl -x https://PROXY_IP:PROXY_PORT https://example.com
```

**For SOCKS4 Proxies**

```bash
curl --socks4 PROXY_IP:PROXY_PORT http://example.com
```

**For SOCKS5 Proxies**

```bash
curl --socks5 PROXY_IP:PROXY_PORT http://example.com
```

-----

## 📜 Disclaimer

Please be aware that public proxies can be unreliable and may pose security risks. We do not guarantee the availability or safety of the proxies listed in this repository. Use them at your own risk. It is recommended to not send any sensitive information when using these proxies.

-----

## 🤝 Contributing

Contributions are welcome\! If you have a list of proxies you would like to add or a suggestion for improving this repository, please feel free to open an issue or submit a pull request.
