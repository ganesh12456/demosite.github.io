# 🔒 Sola Web Security Monitor - Demo Site

This repository contains a demonstration website for the **Website Threat Surface Monitor** project.

## Purpose

This site is designed to test and demonstrate:
- ✅ Sola Web Checker integration
- ✅ WordPress Scanner compatibility  
- ✅ Cloudflare security monitoring
- ✅ GitHub Pages hosting verification
- ✅ AI-powered threat analysis via Sola MCP

## Files Included

| File | Purpose |
|------|---------|
| `index.html` | Main demo website page |
| `sola-verification.txt` | Domain ownership verification for Sola tools |
| `.well-known/security.txt` | Security policy for responsible disclosure |
| `.github/workflows/pages.yml` | Automated GitHub Pages deployment |

## Quick Start

### Deploy to GitHub Pages

1. Push this repository to your GitHub account
2. Go to **Settings → Pages**
3. Select source: **GitHub Actions**
4. The workflow will automatically deploy

Your site will be available at:
```
https://yourusername.github.io/repository-name/
```

## Integration with Website Threat Surface Monitor

Once deployed, add this URL to your monitor's inventory:

```text
Website Inventory
        ↓
Sola Web Checker → https://yourusername.github.io/repo-name/
        ↓
WordPress Scanner → (checks for WP indicators)
        ↓
Cloudflare → (DNS/security headers)
        ↓
GitHub → (repository security settings)
        ↓
Sola MCP
        ↓
AI Analysis
        ↓
Dashboard
```

## Dashboard Example

```
sola-web-security-monitor.github.io

Security Sources:
✓ Sola Web Checker
✓ WordPress Scanner
✓ Cloudflare
✓ GitHub

Risk Score: 78
Grade: B
```

## Testing Verification

Verify the files are accessible:

```bash
# Check main page
curl https://yourusername.github.io/repo-name/

# Check verification file
curl https://yourusername.github.io/repo-name/sola-verification.txt

# Check security policy
curl https://yourusername.github.io/repo-name/.well-known/security.txt
```

## License

MIT License - Free for hackathon and testing purposes