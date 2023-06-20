---
description: This is the example implementation template
---

# Template

The following is a template for the creation of an example implementation. Each use case step can be linked to one or more example implementations. A particular example implementation may be used to address multiple use case steps if the processes are generalized sufficiently.

<table data-header-hidden><thead><tr><th width="238"></th><th></th></tr></thead><tbody><tr><td><strong>Use Case Step</strong></td><td>&#x3C;Provide the name and link to the Use Case Step that this example covers></td></tr><tr><td><p><strong>Preconditions</strong></p><p>(list of conditions that MUST be met in order to be able to successfully execute this process)</p></td><td> </td></tr><tr><td><strong>Data inputs</strong></td><td> </td></tr><tr><td><p><strong>Actors</strong></p><p>(the people, organization, computer systems - hardware and software, and building blocks that participate in the activity)</p></td><td> </td></tr><tr><td><strong>Normal Course</strong> (what happens if the event is triggered and the preconditions have been met)</td><td><p>Provide a step-by-step description of the normal flow of this implementation:</p><ol><li><p>Description of the first thing that happens, including information on data that is entered and/or returned by different actors in the system</p><ol><li>Link to Cucumber test file (or embedded cucumber test) that describes the interaction</li><li>List of APIs that are needed from each BB and link to the API documentation</li><li>List of any data structures that are needed and link to the data structures documentation</li></ol></li><li><p>Description of the second thing that happens, including information on data that is entered and/or returned by different actors in the system</p><ol><li>Link to Cucumber test file (or embedded cucumber test) that describes the interaction</li><li>List of APIs that are needed from each BB and link to the API documentation</li><li>List of any data structures that are needed and link to the data structures documentation</li></ol></li></ol></td></tr><tr><td><p><strong>Alternative Course</strong></p><p>(links to other use cases in case there are different ways how to solve the same use case)</p></td><td>Description of alternate paths or flows that may be needed for this example implementation. These alternates should include links to test files, APIs, and data structures as well</td></tr><tr><td><strong>Data output</strong></td><td> </td></tr><tr><td><strong>Post-Conditions</strong> (the success criteria)</td><td> </td></tr><tr><td><p><strong>Exceptions</strong></p><p>(error situations)</p></td><td>List of error conditions that may be encountered during the normal or alternative flows. Each error condition should provide information on what data will be returned and guidance on how error conditions should be handled by various actors.</td></tr><tr><td><p><strong>Related BBs</strong></p><p>(working groups related to this implementation example)</p></td><td><p>Identity BB</p><p>Consent BB</p><p>Registration BB</p><p>Digital Registries BB</p><p>Payment BB</p></td></tr></tbody></table>

### **Sequence Diagram**

```mermaid
sequenceDiagram
BB1 ->> BB2: Call from BB1 to BB2
BB2 ->> BB1: Response from BB2 to BB1
```

### Links to Code

Provide any links to relevant code that has been developed, such as tests, adaptors and examples, and OpenAPI documentation
