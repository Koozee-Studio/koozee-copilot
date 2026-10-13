# Koozee for GitHub Copilot

Create fashion images and videos with AI—all in one place.

Koozee is an AI visual marketing tool for fashion retailers, brands, and entrepreneurs. Use it with Copilot to create virtual try-ons, on-model lifestyle images, and fashion marketing videos with simple prompts. Let Copilot run workflows to generate images and videos in batches, or build your own on Koozee’s visual canvas. From product listings to marketing campaigns, create compelling visuals and make your products stand out.

This repository is the [Agent Plugins 1.0](https://agent-plugins.org) package for Copilot CLI and Copilot App: `plugin.json`, `mcp.json`, and `skills/` at the repo root.

- Product: [koozee.ai](https://koozee.ai)
- MCP: `https://koozee.ai/business-api/mcp` (`streamable-http`)
- License: MIT

## Install

Clone this repository. The clone root is the plugin root.

```bash
git clone https://github.com/Koozee-Studio/koozee-copilot.git
cd koozee-copilot
copilot plugin install .
```

Copilot App: Customize → Plugins, then install this folder.

The first MCP connection uses OAuth. Calls without login return 401.

Credits match the Koozee canvas. After the canvas changes, open the project URL Koozee returns.

## Support

- Website: https://koozee.ai
- Contact: https://koozee.ai/contact-us
