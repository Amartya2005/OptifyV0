# Optify Setup Notes

The repository keeps the application under the `optify/` directory. When cloning the repository, enter that directory before following the backend and frontend setup steps from `optify/README.md`.

```bash
git clone https://github.com/Amartya2005/OptifyV0.git
cd OptifyV0/optify
```

From there, the documented layout uses:

```text
optify/
├── backend/
└── frontend/
```

The backend requires a `GEMINI_API_KEY` in its environment, while the frontend can be started independently with Vite during development.

This note exists to keep the repository-level clone path and the application-level setup instructions consistent. It also avoids accidentally running the setup commands from the Git repository root when the application files live one directory deeper.
