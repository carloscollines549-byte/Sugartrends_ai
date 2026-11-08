# Sugartrends AI

Repository initialized with an automated OpenRouter code-review workflow.

## OpenRouter review setup

Add a repository Actions secret named `OPENROUTER_API_KEY` containing an OpenRouter API key. The workflow runs on every push to `main`, reviews the pushed diff, and posts its summary as a comment on the resulting commit.
