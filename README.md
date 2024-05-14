## Prompt Attacks Plugin

This plugin allows you to scan attacks from user prompts and agent responses in [PostHog-LLM](https://github.com/postlang/posthog-llm) and [PostHog-LLM-Lite](https://github.com/postlang/posthog-llm-lite). To use this plugin in PostHog-LLM, simply install the [plugin's](https://github.com/minuva/fast-prompt-attack-detect
) backend. The plugin links the PostHog data ingestion process with the hosted detection algorithm.


## How to install in PostHog-LLM

1. Open PostHog-LLM.
2. Open the Data pipeline page from the sidebar.
3. Head to the Manage apps tab.
4. Install app advanced button
5. "Install from GitHub, GitLab or npm" using this repository's URL.
6. Click on apps Apps tab, and it will prompt with API_SERVER_URL (e.g. http://localhost:9612).
