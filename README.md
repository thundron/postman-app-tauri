Silly little experiment running Postman's web interface in Tauri

What doesn't work (that I tried):
- SSO
- offline mode (it loads `https://web.postman.co` so it's dependent on your ISP speed)

Build time:
- cold: `24s`
- hot: `0.10ms`

Bundle size: `~4MB`

Startup time on M1 macbook pro: `~60ms`

