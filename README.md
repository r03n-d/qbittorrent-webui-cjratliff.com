# Dark qBittorrent Web UI theme with fixed .torrent support for iOS[^1]
[^1]: Based on colorscheme from [cjratliff.com](https://cjratliff.com)

![Screenshot](qBittorrent-webui-theme-CJRatliff.com.jpg)

## Installation
- [ ] Open a Terminal session.
- [ ] `cd /etc/`
- [ ] `sudo git clone https://github.com/r03n-d/qbittorrent-webui-cjratliff.com.git`
- [ ] Under Tools->Preferences->WebUI enable Use alternative WebUI.
- [ ] Choose `/etc/qbittorrent-webui-cjratliff.com`
- [ ] Restart qBittorrent or refresh your browser for changes to take effect.

You can also change these settings via the config file. The relevant entries are:

```
WebUI\AlternativeUIEnabled=true
WebUI\RootFolder=/etc/qbittorrent-webui-cjratliff.com
```
