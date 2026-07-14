# Claude-govee-mcp
Govee smart home MCP connector for Claude - control lights, brightness, color, temperature

**Then click "Commit new file"**

---

## FILE 5: server.json

**Location:** Root directory
**Action:** Click "Add file" → "Create new file" → Name it `server.json`

**COPY AND PASTE THIS (and replace YOUR_USERNAME with your GitHub username):**

```json
{
  "name": "govee-mcp",
  "version": "1.0.0",
  "description": "Govee smart home MCP connector - control lights via Claude",
  "author": "Your Name",
  "license": "MIT",
  "homepage": "https://github.com/YOUR_USERNAME/govee-mcp",
  "repository": {
    "type": "git",
    "url": "https://github.com/YOUR_USERNAME/govee-mcp.git"
  },
  "keywords": ["mcp", "govee", "smart-home", "iot", "claude"],
  "entrypoint": "dist/http-server.js",
  "transport": "http",
  "environment": {
    "GOVEE_API_KEY": {
      "required": true,
      "description": "Your Govee Developer API Key"
    }
  }
}
