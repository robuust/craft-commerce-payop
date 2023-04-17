# PayOp for Craft Commerce

This plugin provides [PayOp](https://www.payop.com/) integrations for [Craft Commerce](https://craftcms.com/commerce).

## Requirements

This plugin requires Craft 4.0 and Craft Commerce 4.0 or later.

## Installation

You can install this plugin from the Plugin Store or with Composer.

#### From the Plugin Store

Go to the Plugin Store in your project’s Control Panel and search for PayOp for Craft Commerce”. Then click on the “Install” button in its modal window.

#### With Composer

Open your terminal and run the following commands:

```bash
# go to the project directory
cd /path/to/my-project.test

# tell Composer to load the plugin
composer require robuust/craft-commerce-payop

# tell Craft to install the plugin
./craft install/plugin commerce-payop
```

## Setup

To add a PayOp payment gateway, go to Commerce → Settings → Gateways, create a new gateway, and set the gateway type to PayOp.

> **Tip:** The Key and Token settings can be set to environment variables. See [Environmental Configuration](https://docs.craftcms.com/v3/config/environments.html) in the Craft docs to learn more about that.
