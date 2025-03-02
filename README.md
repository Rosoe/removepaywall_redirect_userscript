# Remove Paywall Redirect Userscript
A lightweight userscript that bypasses paywall redirects while keeping you on the original website's domain. No tracking, no third-party redirects, and completely free to use.

## Features

✅ **Zero Frontpage Redirects** - Will only redirect on articles
⚡ **Lightweight** - Minimal code footprint (under 5KB) for fast execution  
🔧 **Easy to Customize** - Simple pattern matching rules anyone can edit  
🆓 **Completely Free** - No subscriptions, accounts, or hidden costs  
📦 **Self-contained** - No external dependencies or tracking

## Installation
1. Install a userscript manager:
   - [Violentmonkey](https://violentmonkey.github.io/)
   - [Tampermonkey](https://www.tampermonkey.net/)
2. Add the script.

## How It Works
The script uses smart URL pattern matching to:
- Detect paywall redirect attempts in real-time
- Rewrite URLs to bypass tracking parameters

## Contributing
**Want to add more sites?**  
1. Fork this repository
2. Add your URL patterns to `redirectPatterns` array in the script
3. Submit a pull request

I welcome all contributions that help expand coverage while maintaining our core principles of simplicity and transparency.

## License
MIT Licensed - See [LICENSE](LICENSE) for details
