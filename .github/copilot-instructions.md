# Copilot instructions

- Use .NET 10 and C# APIs compatible with the target framework declared by the project. Respect any SDK version pinned in `global.json`.
- Before making changes, inspect the relevant project files, tests, and nearby code; follow their existing structure and conventions.
- Keep changes focused, and avoid adding package dependencies unless they are needed for the requested functionality.
- Preserve the project's nullable reference type, implicit using, analyzer, and formatting settings.
- Prefer asynchronous APIs for I/O, propagate cancellation tokens where supported, and avoid blocking on asynchronous work.
- Add or update tests for behavior changes. Keep tests deterministic and consistent with the existing test framework.
- Run the relevant existing `dotnet test` and `dotnet build` commands after changes, and report any checks that could not be run.
