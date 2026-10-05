# Using VS Code

Use Python 3.9, matching Rhino 8, and the HS26 COMPAS requirements. From the repository root, run:

macOS / Linux:

```sh
bash using-vscode/setup-vscode.sh
```

Windows PowerShell:

```powershell
./using-vscode/setup-vscode.ps1
```

Select `.venv` as the Python interpreter in VS Code. Open `using-vscode_hs26.gh` in Grasshopper and edit `unicorns.py` in VS Code. Keep both files in the same folder.

The Grasshopper components use `# venv: ca-hs26` and `# r: compas>=2.15.1`. This Rhino script environment is separate from the local `.venv`. The example enables `DevTools.enable_reloader()` once and calls `DevTools.ensure_path()` before importing the external module, as in the HS26 teaching repository.
