# Architecture Should Be Understandable

Infrastructure should not depend on a single engineer understanding it.

A healthy platform should be understandable by:

- platform engineers
- developers interacting with the system
- new team members joining months later

If an infrastructure architecture requires extensive tribal knowledge, it will eventually fail operationally.

A good IaC design should therefore emphasize:

- clear structure
- predictable module boundaries
- consistent conventions
- minimal hidden logic

The test of good infrastructure code is not whether it works today.

The test is whether **someone else can safely operate it tomorrow**.
