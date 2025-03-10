# Project Plan: OSCAL + Metaschema Integration

## Project Name
**oscal-metaschema**

## Objective
Create a lightweight, simple-to-use middleware project explicitly bundling NIST's OSCAL schemas with Metaschema to ensure seamless integration, validation, and schema adherence.

## Goals
- Provide a unified schema package combining OSCAL and Metaschema.
- Maintain simplicity, minimalism, and clarity.
- Offer robust examples, tests, and validation tooling.
- Pure - does not deviate from, or modify, the OSCAL or Metaschema schemas.

## Deliverables
- Fully integrated OSCAL + Metaschema schemas (JSON/XSD).
- Example and sample data demonstrating practical usage. Sample data MUST be from NIST.
- Validation scripts/tools.
- Comprehensive test suite ensuring schema compliance.

## Tasks and Milestones

### Phase 1: Preparation
- [ ] Clearly define OSCAL and Metaschema dependencies.
- [ ] Gather latest schemas from NIST repositories.
- [ ] Establish version compatibility matrix (Metaschema ↔ OSCAL).

### Phase 2: Initial Integration
- [ ] Integrate Metaschema schemas into OSCAL schema structure.
- [ ] Ensure internal schema cross-referencing and validation consistency.
- [ ] Create preliminary validation test suite.

### Phase 3: Example and Test Development
- [ ] Develop comprehensive examples covering common OSCAL use cases.
- [ ] Write tests ensuring schemas validate correctly across XML and JSON.
- [ ] Document any schema extension or modifications clearly.

### Phase 3: Automation and CI/CD
- [ ] Automate schema validation using CI/CD pipelines (e.g., GitHub Actions).
- [ ] Publish schemas/package to a central repository (e.g., npm, GitHub packages).

### Phase 4: Documentation
- [ ] Write concise, clear documentation.
- [ ] Provide guidance on integrating the unified schema into downstream projects.
- [ ] Clearly document rationale and benefits of bundling Metaschema explicitly.

### Phase 4: Release
- [ ] Final testing and QA.
- [ ] Tag stable release.
- [ ] Announce release with clear usage examples.

## Deliverables
- Self-contained OSCAL + Metaschema integrated package
- JSON/XML schema files ready for immediate validation
- Clear documentation for easy implementation
- Example and sample data included within the project

## Risks and Mitigation
- **Risk**: Schema drift  
  **Mitigation**: Version matrix clearly maintained in README
- **Risk:** Increased maintenance overhead  
  **Mitigation**: Clearly automated version alignment via CI/CD.
