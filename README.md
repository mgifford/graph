# graph
Simple graph experiments


## Research Workflow
```mermaid
graph TD
    Wireframe-->UXResearch;
    UXResearch-->Wireframe;
    Wireframe-->ProactiveAccessibilityTestingWireframe;
    ProactiveAccessibilityTestingWireframe-->ProductBacklog;
    ProductBacklog-->SprintBacklog;
    ProductBacklog-->ProactiveAccessibilityTestingUXDesign;
    ProductBacklog-->ProactiveAccessibilityTestingUXResearch;
    ProactiveAccessibilityTestingUXDesign-->Wireframe;
    ProactiveAccessibilityTestingUXResearch-->UXResearchReactive;
    UXResearchReactive-->ReactiveAccessibilityTesting;
    ReactiveAccessibilityTesting-->DeployedSystem;
    SprintBacklog-->Sprint;
    Sprint-->Scrum;
    Scrum-->ProaciveAccessibilityTestingSprint;
    ProaciveAccessibilityTestingSprint-->ShipableProduct;
    ShipableProduct-->AccessibilityValidationTesting;
    AccessibilityValidationTesting-->DeployedSystem;
```
