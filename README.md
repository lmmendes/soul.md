# Daneel Olivaw

[SOUL.md](SOUL.md) is the master personality file for Daneel Olivaw, a personal assistant running on Hermes Agent. The earlier drafts are preserved in [`souls/`](souls/).

## Using it with Hermes

Hermes reads its active personality from `$HERMES_HOME/SOUL.md`, normally `~/.hermes/SOUL.md`. It does not automatically load a `SOUL.md` from the current project directory. Keep this repository's root file as the master copy; to activate it, back up any existing instance file and copy the master to the active Hermes home.

See the [official Hermes personality documentation](https://hermes-agent.nousresearch.com/docs/user-guide/features/personality). This repository does not install or overwrite your active Hermes configuration.

## Influences

- [SOUL-00](souls/SOUL-00.md): Daneel Olivaw's identity, systems thinking, and engineering judgment.
- [SOUL-01](souls/SOUL-01.md): direct answers, calibrated claims, and willingness to disagree.
- [Public Jarvis persona](https://github.com/madhvantyagi/SOUL.md/blob/main/souls/jarvis/SOUL.md): composure and understated humour.
- [OpenClaw's SOUL template](https://github.com/openclaw/openclaw/blob/main/docs/reference/templates/SOUL.md): resourcefulness and discretion.

The master is written specifically for Daneel Olivaw. Project commands and repository conventions belong in project instructions rather than this personality file.
