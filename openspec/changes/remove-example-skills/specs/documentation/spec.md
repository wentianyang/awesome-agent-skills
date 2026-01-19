# Documentation Requirements

## ADDED Requirements

### Requirement: Curated Skills Only
The repository SHALL only contain real, verified skills and NOT placeholder examples.

#### Scenario: No placeholder skills
- **Given** the `skills/` directory
- **When** checked for known placeholders like "Creative Writing" or empty example folders
- **Then** they MUST NOT exist.
