# SYSTEM_ROOT // 199X TERMINAL

Early-web / CRT terminal site. Live: http://111.230.151.236/lab1/index.html

## Modules

| File | Index label |
|---|---|
| `galgame.html` | GALGAME.SYS |
| `KAT.html` | KMT.DAT |
| `A_l.html` | SECTION_A.LOG |
| `B.html` | SECTION_B.LOG |
| `cookie.html` | COOKIE_JAR.SYS |
| `DOOM.html` | (linked from KMT) |

## COOKIE_JAR.SYS

AP Cybersecurity midterm: interactive 1996 NAVI_CLUB page that uses **HTTP cookies** for real behavior (consent, session, progress, inventory, prefs, optional tracking log). Open `cookie.html` over HTTP (not `file://`). Demo: DevTools → Application → Cookies.

Typical playthrough ~10 minutes. In-game write-up: **DOCS.TXT**.

## Run locally

```bash
python3 -m http.server 8080
# http://127.0.0.1:8080/
```
