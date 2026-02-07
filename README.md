# n8n-Local-Setup
Setup n8n in local

1. Install Node.js and npm
   - Download and install the latest Node.js (which includes npm) from Node.js official site.
   - Verify Installation:
     ```bash
     node -v
     npm -v
     ```

2. Install n8n Globally
   - Open a terminal (Command Prompt or PowerShell) and run:
     ```bash
     npm install n8n -g
     ```

3. Start n8n
   - Launch n8n by running:
     ```bash
     n8n start
     ```
   - This starts the n8n server locally. By default, it runs on http://localhost:5678.
   - Use `npm update -g n8n` to keep n8n updated.
   - For troubleshooting, refer to [official documentation](https://docs.n8n.io/integrations/creating-nodes/test/run-node-locally/).
