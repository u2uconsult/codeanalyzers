# U2U Consult Code Analyzers

This repository will host the documentation for the U2U Consult diagnostic code analyzers.
Documentation is under construction.

Download the [U2U Consult Performance Code Analyzers for C# 7](https://marketplace.visualstudio.com/items?itemName=vs-publisher-363830.U2UConsultPerformanceCodeAnalyzersforC7)

| Code                       | Description |
| -------------------------- | ----------- |
| [U2U1000](docs/U2U1000.md) | Local variable can be inlined or declared const |
| [U2U1001](docs/U2U1001.md) | Stateless classes can be static |
| [U2U1002](docs/U2U1002.md) | Method can be declared static |
| [U2U1003](docs/U2U1003.md) | Avoid declaring methods used in delegate constructors static |
| [U2U1004](docs/U2U1004.md) | Public value types should implement equality |
| [U2U1005](docs/U2U1005.md) | Implement internal interfaces |
| [U2U1006](docs/U2U1006.md) | Await tasks correctly |
| [U2U1007](docs/U2U1007.md) | Do not call redundant functions |
| [U2U1008](docs/U2U1008.md) | Parentheses can be used to enable constant evaluation |
| [U2U1009](docs/U2U1009.md) | Async or iterator methods should avoid state machine generation for early exits (throws or synchronous returns) |
| [U2U1010](docs/U2U1010.md) | Internal leaf classes can be sealed |
| [U2U1011](docs/U2U1011.md) | Return types should be specific |
| [U2U1012](docs/U2U1012.md) | Parameter types should be specific |
| [U2U1013](docs/U2U1013.md) | Return types should not cause boxing |
| [U2U1014](docs/U2U1014.md) | Parameter types should not cause boxing |
| [U2U1100](docs/U2U1100.md) | Compare strings correctly |
| [U2U1101](docs/U2U1101.md) | Do not concatenate values to strings directly |
| [U2U1102](docs/U2U1102.md) | Do not concatenate char constants |
| [U2U1103](docs/U2U1103.md) | Index strings correctly |
| [U2U1104](docs/U2U1104.md) | Do not use composite formatting to concatenate strings |
| [U2U1105](docs/U2U1105.md) | Do not use string interpolation to concatenate strings |
| [U2U1106](docs/U2U1106.md) | Do not append the result of string concatenation to a StringBuilder |
| [U2U1107](docs/U2U1107.md) | Do not append a single character string to a StringBuilder |
| [U2U1108](docs/U2U1108.md) | StringBuilders should be initialized with capacity |
| [U2U1109](docs/U2U1109.md) | Do not test strings for null when appending to a StringBuilder |
| [U2U1110](docs/U2U1110.md) | Do not append null or empty strings to a StringBuilder |
| [U2U1200](docs/U2U1200.md) | Prefer generic collections over non-generic ones |
| [U2U1201](docs/U2U1201.md) | Local collections should be initialized with capacity |
| [U2U1202](docs/U2U1202.md) | Use LINQ Count methods efficiently |
| [U2U1203](docs/U2U1203.md) | Use foreach efficiently |
| [U2U1204](docs/U2U1204.md) | Do not implicitly convert an IQueryable<T> to an IEnumerable<T> |
| [U2U1205](docs/U2U1205.md) | Do not query a LINQ EntitySet<T> |
| [U2U1206](docs/U2U1206.md) | Do not use a LINQ where clause before filtering the query |
| [U2U1207](docs/U2U1207.md) | Do not aggregate the result of a LINQ select operation |
| [U2U1208](docs/U2U1208.md) | Do not call LINQ methods whose effect is undone by subsequent methods |
| [U2U3000](docs/U2U3000.md) | Provide enough arguments to composite formatting |
| [U2U3001](docs/U2U3001.md) | Use the correct format syntax with composite formatting |
