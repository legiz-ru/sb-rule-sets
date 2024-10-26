# sb-rule-sets

## torrent-clients
<details>
  <summary>json source</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "torrent-clients",
        "outbound": "direct"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "torrent-clients",
        "format": "source",
        "url": "https://raw.githubusercontent.com/legiz-ru/sb-rule-sets/main/torrent-clients.json"
      }
    ]
  }
}
```

</details>
<details>
  <summary>binary rule-set .srs</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "torrent-clients",
        "outbound": "direct"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "torrent-clients",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/legiz-ru/sb-rule-sets/main/torrent-clients.srs"
      }
    ]
  }
}
```

</details>
<details>
  <summary>add to vpnbot</summary>
  
```shell
direct:86400s:https://github.com/legiz-ru/sb-rule-sets/raw/main/torrent-clients.srs
```

</details>

## ru-app-list (android)
<details>
  <summary>json source</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "ru-app-list",
        "outbound": "direct"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "ru-app-list",
        "format": "source",
        "url": "https://raw.githubusercontent.com/legiz-ru/sb-rule-sets/main/ru-app-list.json"
      }
    ]
  }
}
```

</details>
<details>
  <summary>binary rule-set .srs</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "ru-app-list",
        "outbound": "direct"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "ru-app-list",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/legiz-ru/sb-rule-sets/main/ru-app-list.srs"
      }
    ]
  }
}
```

</details>
<details>
  <summary>add to vpnbot</summary>
  
```shell
direct:86400s:https://github.com/legiz-ru/sb-rule-sets/raw/main/ru-app-list.srs
```

</details>

## unbanru-app-list (android+windows)
<details>
  <summary>json source</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "unbanru-app-list",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "unbanru-app-list",
        "format": "source",
        "url": "https://raw.githubusercontent.com/legiz-ru/sb-rule-sets/main/unbanru-app-list.json"
      }
    ]
  }
}
```

</details>
<details>
  <summary>binary rule-set .srs</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "unbanru-app-list",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "unbanru-app-list",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/legiz-ru/sb-rule-sets/main/unbanru-app-list.srs"
      }
    ]
  }
}
```

</details>
<details>
  <summary>add to vpnbot</summary>
  
```shell
proxy:86400s:https://github.com/legiz-ru/sb-rule-sets/raw/main/unbanru-app-list.srs
```

</details>

## no-russia-hosts
This rule-set generated from [this domain list](https://github.com/dartraiden/no-russia-hosts)

<details>
  <summary>json source</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "no-russia-hosts",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "no-russia-hosts",
        "format": "source",
        "url": "https://github.com/legiz-ru/sb-rule-sets/raw/main/no-russia-hosts.json"
      }
    ]
  }
}
```

</details>
<details>
  <summary>binary rule-set .srs</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "no-russia-hosts",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "no-russia-hosts",
        "format": "binary",
        "url": "https://github.com/legiz-ru/sb-rule-sets/raw/main/no-russia-hosts.srs"
      }
    ]
  }
}
```

</details>
<details>
  <summary>add to vpnbot</summary>
  
```shell
proxy:86400s:https://github.com/legiz-ru/sb-rule-sets/raw/main/no-russia-hosts.srs
```

</details>

