# Contributing to Stellar Engine

## Branch Naming Convention

- `feature/M4-scene-graph` — nuove funzionalità (riferimento milestone)
- `fix/memory-leak-pool`   — bugfix
- `refactor/render-rhi`    — refactoring senza cambio di comportamento
- `docs/api-renderer`      — solo documentazione

## Commit Messages (Conventional Commits)

Format: `<type>(scope): <description>`

Examples:

- `feat(foundation): add LinearAllocator with RAII wrapper`
- `fix(renderer): correct depth buffer clear order`
- `test(ecs): add SceneGraph traversal unit tests`
- `docs(api): document IRenderDevice public interface`

## Pull Request Process

1. Branch from `dev`, never from `main`
2. All CI checks must pass
3. Code coverage must not decrease
4. Doxygen comments required for all public API
