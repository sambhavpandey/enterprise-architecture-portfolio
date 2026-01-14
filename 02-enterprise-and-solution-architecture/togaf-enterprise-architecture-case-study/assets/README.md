# Assets Repository

This folder contains all visual and supporting artefacts used across the TOGAF case study.

## Folder Structure

### diagrams/
Architecture and business diagrams:
- Value stream maps  
- Capability maps  
- Architecture views (current and target)  
- Transition architectures  
- Roadmaps  

Recommended formats:
- PNG for GitHub viewing  
- Draw.io XML for editing  
- PDF for sharing  

### images/
Supporting visuals:
- Screenshots  
- Reference diagrams  
- Concept illustrations  

### tables/
Structured data used in artefacts:
- Application inventory  
- Capability lists  
- Gap analysis tables  
- Traceability matrices  
- Cost and benefit tables  

Recommended formats:
- Excel for calculations  
- CSV for portability  
- PNG for embedded visuals  

## Naming Convention

Use clear, ordered names:

diagrams/
- 01-architecture-vision.png  
- 02-business-capability-map.png  
- 03-current-application-architecture.png  
- 04-target-application-architecture.png  
- 05-transition-architecture.png  
- 06-phased-roadmap.png  

tables/
- application-inventory.xlsx  
- business-capability-map.xlsx  
- gap-analysis.xlsx  
- traceability-matrix.xlsx  
- cost-benefit-model.xlsx  

images/
- workshop-session.png  
- reference-architecture.png  

## Usage

Each markdown file in the main folders should reference diagrams and tables from here using relative paths.
Example:

```md
![Target Architecture](../assets/diagrams/04-target-application-architecture.png)
