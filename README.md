# U2U Consult Code Analyzers

This repository will host the documentation for the U2U Consult diagnostic code analyzers.
Documentation is under construction.

Download the [U2U Consult Performance Code Analyzers for C# 7](https://marketplace.visualstudio.com/items?itemName=vs-publisher-363830.U2UConsultPerformanceCodeAnalyzersforC7)

| U2U1000 | Local variable can be inlined or declared const |
| U2U1001 | Stateless classes can be static |
| U2U1002 | Method can be declared static |
| U2U1003 | Avoid declaring methods used in delegate constructors static |
| U2U1004 | Public value types should implement equality |
| U2U1005 | Implement internal interfaces |
| U2U1006 | Await tasks correctly |
| U2U1007 | Do not call redundant functions |
| U2U1008 | Parentheses can be used to enable constant evaluation |
| U2U1009 | Async or iterator methods should avoid state machine generation for early exits (throws or synchronous returns) |
| U2U1010 | Internal leaf classes can be sealed |
| U2U1011 | Return types should be specific |
| U2U1012 | Parameter types should be specific |
| U2U1013 | Return types should not cause boxing |
| U2U1014 | Parameter types should not cause boxing |
| U2U1100 | Compare strings correctly |
| U2U1101 | Do not concatenate values to strings directly |
| U2U1102 | Do not concatenate char constants |
| U2U1103 | Index strings correctly |
| U2U1104 | Do not use composite formatting to concatenate strings |
| U2U1105 | Do not use string interpolation to concatenate strings |
| U2U1106 | Do not append the result of string concatenation to a StringBuilder |
| U2U1107 | Do not append a single character string to a StringBuilder |
| U2U1108 | StringBuilders should be initialized with capacity |
| U2U1109 | Do not test strings for null when appending to a StringBuilder |
| U2U1110 | Do not append null or empty strings to a StringBuilder |
| U2U1200 | Prefer generic collections over non-generic ones |
| U2U1201 | Local collections should be initialized with capacity |
| U2U1202 | Use LINQ Count methods efficiently |
| U2U1203 | Use foreach efficiently |
| U2U1204 | Do not implicitly convert an IQueryable<T> to an IEnumerable<T> |
| U2U1205 | Do not query a LINQ EntitySet<T> |
| U2U1206 | Do not use a LINQ where clause before filtering the query |
| U2U1207 | Do not aggregate the result of a LINQ select operation |
| U2U1208 | Do not call LINQ methods whose effect is undone by subsequent methods |
| U2U3000 | Provide enough arguments to composite formatting |
| U2U3001 | Use the correct format syntax with composite formatting |