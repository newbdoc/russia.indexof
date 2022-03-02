# russia.indexof
Export list of files available for free in russia - directorylisting/indexof

---

*Directory*

```sh
├── json    - format = json, content = extract by filetype (only few filetype). exemple .sql, .tgz, .config, .ovpn, etc...
├── csv     - format = csv, content = same as json . . . but in .csv . . . 
├── html    - html (first level) 1 file per/port
└── txt     - Extraction of file from html. 1 file per ip/port.
```

**Format of the JSON :**

filename : ru_files_ovpn.json
```sh
jq . ru_files_ovpn.json
{
  "scantime": "2022-02-23T20:40:27.106049",
  "ip": "146.255.188.11",
  "port": 80,
  "host": "146.255.188.11",
  "link": "2.ovpn",
  "org": "Alex Group LLC",
  "asn": "AS52000",
  "city": "Ramenskoye",
  "isp": "Innovation IT Solutions LTD",
  "shodanmodule": "http",
  "sslsubject": null,
  "province": "MOS",
  "hash": 12546670,
  "html_hash": -349781053,
  "product": "Apache httpd",
  "ssl_jarm": null,
  "sslissuer": null,
  "country": "Russian Federation"
}
{
  "scantime": "2022-02-24T06:10:00.080487",
  "ip": "91.197.195.3",
  "port": 84,
  "host": "91.197.195.3",
  "link": "gw1-UDP4-1198-audit-config.ovpn",
  "org": "JSC Avantel",
  "asn": "AS51178",
  "city": "Saint Petersburg",
  "isp": "JSC Avantel",
  "shodanmodule": "http-simple-new",
  "sslsubject": null,
  "province": "SPE",
  "hash": 2069945086,
  "html_hash": 662343617,
  "product": "Apache httpd",
  "ssl_jarm": null,
  "sslissuer": null,
  "country": "Russian Federation"
}

```
