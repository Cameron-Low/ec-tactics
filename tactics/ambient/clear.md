# Syntax
`clear` or
`clear -<idents>`, where `<idents>` is a nonempty space separated list of identifiers.
# Overview
Removes everything from the context except the list of identifiers provided (if provided) and identifiers used in them or the goal transitively.
# Notes
This will remove all hypotheses unless they are explicitly excluded or are moved to the goal.
