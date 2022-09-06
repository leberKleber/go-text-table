# go-text-table

`go-text-table` is a go-library to encode and decode text table like the output of the unix network-manager command
`nmcli dev wifi`:

```shell
➜  ~ nmcli dev wifi 
IN-USE  BSSID              SSID                MODE   CHAN  RATE        SIGNAL  BARS  SECURITY  
        3C:37:12:79:85:1D  FRITZ!Box 9999 NT   Infra  11    130 Mbit/s  100     ▂▄▆█  WPA2      
*       3C:37:12:79:85:1D  FRITZ!Box 9999 NT   Infra  52    270 Mbit/s  97      ▂▄▆█  WPA2      
        18:37:8C:A4:66:1D  Martin Router King  Infra  6     540 Mbit/s  82      ▂▄▆█  WPA2      
        18:37:8C:A4:66:1D  --                  Infra  100   540 Mbit/s  37      ▂▄__  WPA2      
        18:37:8C:A4:66:1D  --                  Infra  100   540 Mbit/s  35      ▂▄__  WPA2      
        1A:37:8C:A4:66:1D  --                  Infra  100   540 Mbit/s  35      ▂▄__  WPA2      
        74:37:7F:86:83:1D  Wild WLAN Router    Infra  6     130 Mbit/s  30      ▂___  WPA2      
```

## Features

| Issue | Name               | Status              |
|-------|--------------------|---------------------|
| #1    | Unmarshal (static) | X (not implemented) |
| #2    | Marshal (static)   | X (not implemented) |
| #3    | Encode (stream)    | X (not implemented) |
| #4    | Decode (stream)    | X (not implemented) |
