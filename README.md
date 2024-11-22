# fs-uae-demo-viewports
Viewport settings for various Amiga demos for use in FS-UAE.

Contributions / fixes / ideas welcome.

### Global fs-uae-launcher Options

The following are what I use in the Advanced section of the fs-uar-launcher.

Tweak to suit your preference, but these work well for a 1080p display.

```
bezel = 0
border = 0
crop = 0
fullscreen_height = 1080
fullscreen_width = 1920
line_doubling = 1
log_autoscale = 0
quick_settings = 1
scale = 1
scanlines = 0
smoothing = 0
```

Any of these can be overridden in the Custom per-demo config section (cog icon).

### fs-uae-launcher Video Options

If an option isn't mentioned here, it's your choice, but this is what I use.

- Start in fullscreen: On
- Zoom: Auto (this **_must_** be Auto for viewports to work)
- Keep aspect: On
- Render scanlines (never used RTG): Both Off
- Video sync: Auto

### fs-uae-launcher Advanced Video Options

- Fullscreen Desktop (default)
- 32 Bit (default)
- Low latency sync: On
- FSAA: Off
- Texture filter: default
- Texture format: default
- Video Sync Method: Up to you. I use swap-fence as it's recommended for Nvidia drivers in the FS-UAE doco.

