# Access ends when a Refund Request is approved, not when the Refund is issued

A learner loses access to a course the moment an admin approves their Refund Request, regardless of whether the Refund is still Pending, Issued, or Failed. We tie access to the decision rather than the money because the decision is final and a Failed Refund leaves the request approved: following the money would make access flicker on and off with payment problems that have nothing to do with whether the learner should keep the course.

## Consequences

- A learner whose Refund is stuck as Pending or Failed has neither the course nor their money. Resolving that is an admin's job on the Refund side, not something to fix by restoring access.
- Access is ended by marking the enrollment as ended, not deleting it, so the learner's progress and watch history survive. If they buy the course again they resume where they left off, and their earlier watch time still counts towards Refund Eligibility.
