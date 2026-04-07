# SocOps Workspace Instructions

## Mandatory Development Checklist
Before finishing any implementation, run and report these checks:
- Lint: dotnet format --verify-no-changes SocOps/SocOps.csproj
- Build: dotnet build SocOps/SocOps.csproj
- Test: dotnet test vscode-agent-lab-soc-ops-csharp.sln

## Project Scope
- App type: .NET 10 Blazor WebAssembly in SocOps.
- UI: SocOps/Components.
- Domain models: SocOps/Models.
- Game logic/services: SocOps/Services.
- Styles/assets: SocOps/wwwroot.

## Implementation Rules
- Keep changes minimal and focused.
- Preserve nullable safety and implicit usings from SocOps/SocOps.csproj.
- Keep UI behavior in Razor components and gameplay rules in services.
- Register new services in SocOps/Program.cs via dependency injection.
- Prefer small, composable components.
- Avoid adding dependencies unless clearly justified.

## Styling Rules
- Reuse utilities in SocOps/wwwroot/css/app.css first.
- Add new utilities in the same low-specificity, single-purpose style.
- Keep spacing and visual language consistent with existing screens.

## Reliability Rules
- Do not remove existing behavior unless explicitly requested.
- For gameplay changes, verify core game flow still starts and works.
- For substantial edits, always run the full mandatory checklist.
