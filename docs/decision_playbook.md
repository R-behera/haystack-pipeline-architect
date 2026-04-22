# Decision Playbook

## User

Claims reviewers and underwriters working inside the insurance policy Q&A workflow.

## Decision to support

Determine whether a policy answer is strong enough to use in live claim handling without escalating for manual legal or underwriting review.

## Triage path

1. Ask the policy question through the grounded search flow.
2. Confirm that the answer cites the exact clause or endorsement language.
3. Check whether the cited text matches the claim type, state, and policy form in scope.
4. Escalate if the answer relies on weak or missing evidence, conflicting endorsements, or a jurisdiction-specific exception.

## Escalation triggers

- No clause or endorsement citation is returned.
- The retrieved language references a different policy form or line of business.
- Exclusion language and exception language conflict.
- The answer depends on state-specific handling guidance that is not present in the evidence set.

## Operator output

The final operator note should include:

- the clause or endorsement used
- the likely decision path
- whether legal or underwriting escalation is needed
- the next document or fact required to close the claim decision
