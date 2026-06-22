# SRE Tech WooCommerce Gateway

A WooCommerce payment gateway plugin that allows merchants to accept payments via SRE Tech. Supports both hosted (redirect) and widget (embedded iframe) payment flows.

## Features

- Two payment flows: Hosted (redirect to SRE Tech) or Widget (embedded iframe on checkout)
- Sandbox and production environment support
- Automatic order status management with abandonment detection
- Server-to-server callback and browser-based polling for payment verification
- Server-side fallback check for missed payments
- Debug timeline on order pages for transaction troubleshooting
- WooCommerce Blocks checkout support

## Requirements

- WordPress 5.8+
- WooCommerce 6.0+
- PHP 7.4+
- A SRE Tech merchant account and API key

## Installation

1. Upload the plugin files to `/wp-content/plugins/wc-sretech-gateway/`
2. Activate the plugin through the WordPress Plugins screen
3. Go to WooCommerce → Settings → Payments → SRE Tech to configure
4. Enter your API key and choose your preferred payment flow
5. Visit Settings → Permalinks and click "Save Changes" to activate the return URL endpoint
