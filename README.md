# Embedded Games for PSG1: PlaySolana Matrix Hackathon Submission

This repository is the hackathon submission that ties together three project parts as git submodules: the frontend, backend, and Unity assets. The actual project code lives in the individual repositories included as submodules.

**Overview**
- **What:** A bundled repo for judging that includes the full system via submodules.
- **Included submodules:** `embedded-frontend`, `embedded-backend`, `Embedded-unity` (see links below).

**Quick Start for Judges**

Clone this repository with all submodules in one step:

```bash
git clone --recurse-submodules <repo-url>
```

If you've already cloned the repo, fetch and initialize submodules with:

```bash
git submodule update --init --recursive
```

If any submodule fails to fetch (network, permissions or hosting restrictions), you can clone the submodules manually into their folder names, then run the update command above.

**Original Submodule Repositories**
If the submodules cannot be obtained from this bundle, fetch them directly from their source repositories:

- Frontend: https://github.com/PsyLabsWeb3/embedded-frontend.git
- Backend:  https://github.com/PsyLabsWeb3/embedded-backend.git
- Unity:    https://github.com/PsyLabsWeb3/Embedded-unity.git

**Repository Layout (top-level)**
- `embedded-frontend/` - frontend app and assets
- `embedded-backend/`  - backend API, prisma schema, scripts
- `Embedded-unity/`    - Unity projects and assets

**Notes for Judges**
- Use the `--recurse-submodules` clone flag for the smoothest experience.
- If you encounter access or network issues, clone the submodules directly using the links above and then run `git submodule update --init --recursive`.

Thank you for reviewing our hackathon submission. Enjoy testing the project!
