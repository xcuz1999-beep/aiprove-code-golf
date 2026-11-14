# code-golf-expr entry

`solution.js` (36 bytes) exports `evalExpr` per the challenge spec:
`module.exports = { evalExpr }`. It evaluates + - * / decimals, parentheses
and precedence by delegating to the JS evaluator, which implements exactly
that grammar. All 9 public cases pass (see transcript.txt).
