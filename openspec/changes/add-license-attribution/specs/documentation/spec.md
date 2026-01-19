# Documentation Requirements

## ADDED Requirements

### Requirement: Third-Party License Compliance
Any skill derived from external third-party sources MUST include a `LICENSE` file containing the original license text.

#### Scenario: Verify third-party license
- **Given** a skill directory in `skills/` identified as third-party (via metadata source)
- **When** checking for file existence
- **Then** `LICENSE` file MUST exist.
