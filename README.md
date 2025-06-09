# SOVA Chatbot – Microsoft Copilot Studio (No-Code Project)

This repository contains the configuration and documentation for the SOVA chatbot, developed for the Prague University of Economics and Business using [Microsoft Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)—a no-code, SaaS AI orchestration platform.

## What’s Included

- **Agent YAML exports:** Full configuration for restoring or redeploying the Copilot Studio agent.
- **Solution Documentation:** Technical report, initial business and technical "proposal" (`/docs/`).
- **Limitations:** Notes on reproducibility and what cannot be exported from Copilot Studio. - TBD

## About This Repo

Because Copilot Studio is a no-code platform, there is no traditional application source code. All business logic, retrieval orchestration, and AI prompt engineering is managed via the platform UI and exported as YAML configuration files.

To reproduce the agent, import the provided YAML files into your Copilot Studio environment.

## References

- [Technical Documentation](docs/solution-architecture.pdf)
- [Copilot Studio Official Docs](https://learn.microsoft.com/en-us/microsoft-copilot-studio/)

## Limitations

Some Copilot Studio features and settings may not be fully captured in the YAML export. Certain logic (such as retrieval flows or UI customizations) may require additional manual setup after import.

---

If you have any questions or require further details, please contact the project team lead. novm63@vse.cz
