# gophish-clean

Gophish version cleaned from well-known signatures to avoid detection 

Removed:

- X-Server header
- X-Gophish headers
- X-Mailer header
- renamed rid parameter to userid

## How to use

Tested with Go v1.14 and gcc

```
git clone https://github.com/vflame6/gophish-clean.git
cd gophish-clean
go build
```

## Other IoCs

If you know others IoC of Gophish, please create an issue with its description.
