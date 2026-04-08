# hermes-webui-aio
Combined repo containing the hermes agent and hermes-webui (imported).

Structure:
- /hermes          (imported from nesquena/hermes)
- /hermes-webui    (scaffold imported from CodeEagle/lzcat-apps/apps/hermes-webui)


## Local development (docker-compose)

Run both services locally for development:

  docker compose up --build

This will build the hermes agent and hermes-webui from the local folders.

Adjust HERMES_AGENT_URL or published ports in docker-compose.yml if needed.

