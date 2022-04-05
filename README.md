# Synapse Data Model

Synapse is a versatile central intelligence and analysis system created to
support analyst teams in every stage of the intelligence life cycle.

Synapse’s data store (known as a Cortex) is organized as a hypergraph. Combined
with its structured and extensible Data Model and the powerful and intuitive
Storm query language, Synapse gives analysts unparalleled power and flexibility
to ask and answer any question, even over large and complex data sets.

(From: https://synapse.docs.vertex.link/en/latest/synapse/intro.html)

However, the data model is hard coded in Python classes, which makes code
generation for other programming language harder. As the data model is often
updated, manually maintaining multiple programming language bindings is a very
time consuming tasks.

JSON Schema is a vocabulary that allows you to annotate and validate JSON
documents. From JSON schema, you can also generate code (e.g. for the data
model used in a back-end) or generate forms (for the user interface.)

This repository is an export of the latest released data model used by Vertex
Synapse.

The documentation of the data model is available at
https://synapse.docs.vertex.link/en/latest/synapse/datamodel.html
