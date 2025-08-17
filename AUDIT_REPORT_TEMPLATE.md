# High Severity
### [H-#]

**Description:** 

- Problem statement: Critical flaw directly affecting funds or contract functionality.

- Consequence: Leads to loss of user funds, system-wide failure, or permanent denial of service.

- Code reference + environment: Show vulnerable code with compiler version / context.

- Risk summary: Exploitation may result in severe financial loss or protocol compromise.

**Impact:**

- Loss of user funds, critical contract failure, or protocol-wide shutdown.

- Affects all users and the protocol owner.

**Proof of Concept:**

- Show an exploit test, attacker scenario, or clear steps to trigger the issue.

**Recommended Mitigation:**

- Apply urgent fix (use secure libraries, strict validation, redesign logic).


# Medium Severity
### [M-#]

**Description:** 

- Problem statement: Issue may cause incorrect behavior under certain conditions.

- Consequence: Could lead to fund miscalculation, privilege misuse, or temporary malfunction.

- Code reference + environment: Include vulnerable snippet.

- Risk summary: Not always exploitable, but dangerous in specific scenarios.

**Impact:**

- Potential fund miscalculation or partial denial of service.

- Affects some users or contract owner under certain inputs.

**Proof of Concept:**

- Provide a test case or scenario where the bug can appear.

**Recommended Mitigation:**

- Strengthen validation, use safer data types, or update logic.


# Low Severity
### [L-#]

**Description:** 

- Problem statement: Minor issue in logic or implementation.

- Consequence: May cause small inconsistencies or limited unexpected behavior.

- Code reference + environment: Include code line.

- Risk summary: Does not threaten core security, but reduces reliability.

**Impact:**

- Minor miscalculations, slight disruption, or restricted misuse.

- Affects specific edge cases.

**Proof of Concept:**

- Small test case showing unintended behavior.

**Recommended Mitigation:**

- Simple code fix or input validation.


# Informational
### [I-#]

**Description:** 

- Problem statement: Non-critical finding related to readability, best practices, or documentation.

- Consequence: No direct security risk, but may confuse developers or reduce maintainability.

- Code reference + environment: Mention the line or area of concern.

- Risk summary: Informational only; no impact on protocol security.

**Impact:**

- No direct financial or functional risk.

- Affects developers or maintainability only.

**Proof of Concept:**

- Example of unclear or non-standard practice.

**Recommended Mitigation:**

- Follow style guide, add comments, rename variables, or restructure for clarity.


# Gas Optimization
### [G-#]

**Description:** 

- Problem statement: Inefficient code pattern increasing gas costs.

- Consequence: Users pay higher transaction fees unnecessarily.

- Code reference + environment: Point to inefficient loop, storage write, or redundant operation.

- Risk summary: No security issue, but wastes gas.

**Impact:**

- Increased gas cost per transaction.

- Affects all users interacting with the function.

**Proof of Concept:**

- Compare current gas usage vs optimized version.

**Recommended Mitigation:**

- Apply micro-optimizations (use unchecked where safe, reduce storage writes, refactor loops).
