# Notes of the book *Design and Build Great Web APIs* by Michael Amundsen

## Phase 0: Modeling APIs

Discovery of facts around an API involves two key steps.

1. *Map out the API workflow and identify the internal cycles*. This API workflow document helps you get the big picture of what you’re working on. The internal cycles document helps you focus on the details of each small step in the overall workflow.

2. *Write an API story document*. A narrative document that explains just what the API is meant to do, along with the data properties and actions that “animate” that story.

These two steps are iterated again and again, until there's enough information to initialize the first iteration of next major phase: Designing APIs

## Phase 1: Designing APIs

Four kinds of artifacts:

* *Descriptor*: name convention for nouns and verbs
* *Diagram*: visualization of workflow and internal cycles
* *Definition*: a machine-readable API definition document for further implementation
* *Documentation*: basic reference documentation for both service developers and service consumers (those using the API in the future).

These artifacts are also created and updated iteratively.

![API Design Artifacts](./images/api-design-artifacts.png "API Design Artifacts")

### Identifying our API Descriptors

* Use [schema.org](https://schema.org/) as a source for validating vocabularies. Example see: [Art-Library-API-Workflow.txt](./assets/Art-Library-API-Workflow.txt)
* For banking industry perticularly interesting: [Banking Industry Architecture Network (BIAN)](https://bian.org/)
* Common types of names:
  - data names (Artwork)
  - action names (CreateArtwork)
  - state names (CreatedArtwork)

