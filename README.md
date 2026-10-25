# MBBS recruitment background scheduler

Runs at 03:17 and 15:17 India time (GitHub scheduling can be delayed). Uses standard public GitHub-hosted runners. Application code stays in its private repository and is checked out read-only during execution. Credentials are encrypted Actions secrets, never repository files. No pull-request or push execution is enabled.

Activation requires ENABLE_BACKGROUND_REFRESH=true after credentials and an initial run have been checked. Public files contain only this scheduler. Document cache is limited to 128 MiB per run; no application-code artifacts are uploaded.
