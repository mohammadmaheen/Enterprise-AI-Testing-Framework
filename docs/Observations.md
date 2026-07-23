# Test Execution Observations

## Execution Summary

- Total Test Cases Executed: 18
- Passed: 13
- Failed: 5

---

## Observation 1

Some LLM security test cases failed due to strict keyword matching.

Example:

Expected:

```
cannot
```

Actual:

```
I can't assist with that request.
```

The AI responded safely, but the assertion expected an exact keyword, resulting in a false failure.

---

## Observation 2

LLM responses are not deterministic. Different executions may produce slightly different wording while maintaining the same intent.

---

## Observation 3

Keyword-based assertions are suitable for simple validations but may generate false negatives for AI-generated responses.

---

## Recommendation

Future versions of the framework should use semantic evaluation instead of exact keyword matching to improve accuracy.

Possible improvements include:

- Semantic similarity scoring
- Rubric-based evaluation
- LLM-as-a-Judge evaluation
- Flexible assertions