# sb-rule-sets

## ru-bundle (itdoginfo-inside-russia+no-russia-hosts)
### NOT PRODUCTION RULESET, MAYBE NOT STABLE
<details>
  <summary>json source</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "ru-bundle",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "ru-bundle",
        "format": "source",
        "url": "https://github.com/legiz-ru/sb-rule-sets/raw/main/ru-bundle.json"
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
        "rule_set": "ru-bundle",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "ru-bundle",
        "format": "binary",
        "url": "https://github.com/legiz-ru/sb-rule-sets/raw/main/ru-bundle.srs"
      }
    ]
  }
}
```

</details>
<details>
  <summary>add to vpnbot</summary>
  
```shell
proxy:86400s:https://github.com/legiz-ru/sb-rule-sets/raw/main/ru-bundle.srs
```

</details>

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

## itdoginfo-inside-russia
This rule-set generated from [this domain list](https://github.com/itdoginfo/allow-domains/blob/main/src/Russia-domains-inside.lst)

<details>
  <summary>json source</summary>
  
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "itdoginfo-inside-russia",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "itdoginfo-inside-russia",
        "format": "source",
        "url": "https://github.com/legiz-ru/sb-rule-sets/raw/main/itdoginfo-inside-russia.json"
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
        "rule_set": "itdoginfo-inside-russia",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "itdoginfo-inside-russia",
        "format": "binary",
        "url": "https://github.com/legiz-ru/sb-rule-sets/raw/main/itdoginfo-inside-russia.srs"
      }
    ]
  }
}
```

</details>
<details>
  <summary>add to vpnbot</summary>
  
```shell
proxy:86400s:https://github.com/legiz-ru/sb-rule-sets/raw/main/itdoginfo-inside-russia.srs
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

# another good rulesets
- [RU rulesets for Sing-Box](https://github.com/burjuyz/RuRulesets?tab=readme-ov-file#%D0%BF%D1%80%D1%8F%D0%BC%D1%8B%D0%B5-%D1%81%D1%81%D1%8B%D0%BB%D0%BA%D0%B8) by burjuyz
- [Альтернативный список заблокированных в РФ ресурсов Re:filter](https://github.com/1andrevich/Re-filter-lists?tab=readme-ov-file#%D0%BF%D1%80%D0%B8%D0%BC%D0%B5%D1%80-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-sing-box)

