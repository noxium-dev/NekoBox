# Quick Start Guide

## Initial Setup

### 1. Set Download Folder
1. Open NekoBox
2. Navigate to **Settings**
3. Click **Download Location**
4. Click **Browse** and select your desired folder
5. Click **Save**

### 2. Test Gallery-dl (Optional)
If you installed gallery-dl:
1. Go to **Settings**
2. Click **Gallery-dl Diagnostics**
3. Click **Test Gallery-dl**
4. Verify it shows as installed and working

## Downloading Content

### Single Mode (Individual URLs)

1. Switch to the **Download** tab
2. Select **Single Mode**
3. Paste one or more URLs (one per line):
   - Direct image links
   - Post/artwork URLs
   - Tweet URLs
4. Click **Start Download**

**Example URLs:**
```
https://www.pixiv.net/artworks/123456789
https://rule34.xxx/index.php?page=post&s=view&id=123456
```

### Batch Mode (Galleries & Profiles)

1. Switch to the **Download** tab
2. Select **Batch Mode**
3. Paste a gallery or profile URL:
   - Pixiv user profile
   - Rule34 tag search
   - Reddit subreddit
4. Set download limit (or leave unlimited)
5. Click **Start Download**

**Example URLs:**
```
https://www.pixiv.net/users/12345
https://rule34.xxx/index.php?page=post&s=list&tags=example
```

## Managing Downloads

### Queue Tab
- View all active and completed downloads
- See overall progress
- Individual file progress with MB display
- Real-time speed monitoring

### Controls
- **Pause**: Click pause button on any download
- **Resume**: Click resume on paused downloads
- **Expand**: Click download card to see individual files
- **Cancel**: Stop and remove from queue

## Tips & Tricks

### Authentication-Required Sites
Some sites (like Pixiv) require authentication:
1. Export cookies from your browser using a cookie export extension
2. Save as `cookies.txt` in Netscape format
3. Go to **Settings** → **Authentication**
4. Import your cookie file

### Download Speed
- Adjust concurrent downloads in **Settings** (5-50)
- Higher numbers = faster overall, but more resource usage
- Lower numbers = more stable, better for slower connections

### File Naming
Customize how files are named in **Settings**:
- Add prefixes
- Include artist names
- Add date stamps
- Custom patterns

## Troubleshooting

### "Gallery-dl not found"
- Make sure you installed it: `pip install gallery-dl`
- Restart NekoBox after installation

### "Authentication required"
- Export cookies from your browser for that site
- Import cookies in Settings

### Downloads stuck
- Check your internet connection
- Try pausing and resuming
- Restart the application

### Files not saving
- Check download folder permissions
- Make sure you have enough disk space
- Verify the folder path is correct

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | New Download |
| `Ctrl+Q` | Open Queue |
| `Ctrl+,` | Open Settings |
| `Ctrl+R` | Refresh |

---

Need more help? Check the main [README](README.md) or [Supported Sites](SUPPORTED_SITES.md).
