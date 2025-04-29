# Risk Management Plan

## Identified Risks and Responses

| Risk                                                  | Likelihood | Impact | Mitigation Strategy                            |
|-------------------------------------------------------|------------|--------|--------------------------------------------------|
| Firebase notification misconfiguration                | Medium     | High   | Use Firebase Test Console + emulator validation |
| Time conflict between team members                    | High       | Medium | Define async workflows, clear GitHub issues     |
| Data loss due to misconfigured DB                     | Low        | High   | Use Django migrations with strict schema rules  |
| Code conflicts on GitHub                              | Medium     | Medium | Branch-based dev model, enforced PR reviews     |
| Mobile emulator behaving differently from real device | High       | Medium | Include real-device testing before submission   |

## Weekly Review

Risks were reviewed during sprint retrospectives. GitHub issues marked with `risk` tag were highlighted and resolved first.
