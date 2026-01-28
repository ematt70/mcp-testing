# mcp-testing
testing repo for mcp experiments

## SETUP
See [Building an MCP Server doc](https://modelcontextprotocol.io/docs/develop/build-server)

## QUICK SETUP
create an .env file and give it the following:

ANTHROPIC_API_KEY=(your key here)

Get an api key from anthropic by going [here](https://console.anthropic.com/settings/keys)

Then either run the mcp server by:

1. Run on command line
    1. export ANTHROPIC_API_KEY=(your key here)
    2. cd mcp-client
    3. python3 client.py ../weather/weather.py
