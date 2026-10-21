# Changelog

## 1.0.1
- Agent types now use the API values in `metadata.aws-devops-agent-skills.agent-types` (`CHAT`, `INCIDENT_RCA`, `INCIDENT_TRIAGE`), the field that sets which agents load the skill.

## 1.0.0

- Initial version
- Skip MEDIUM and LOW severity incidents during maintenance window (2025-03-15 02:00–06:00 UTC)
- Preserve investigation for HIGH and CRITICAL severity incidents
