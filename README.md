# VisualFeedbackLab
Librairie modulaire de feedback visuel réutilisable pour Unity.

## Deliverables
- 6 transform modules
- 6 utility shaders
- 6 particle primitives
- 6 recipes
- 1 sandbox scene
- 1 minimal documentation

## Out of Scope
- genre-specific effects
- cinematic effects
- heavy editor tooling
- game-specific logic
- polished content beyond reusability needs

## Architecture Rules
- one module = one responsibility
- testable in isolation
- parameterized
- recipes = composition only
- no game-specific naming
- reusable across projects

## Success Criteria
- portable to another project
- triggerable quickly
- composable without rewrite
- individually testable
- mostly generic
