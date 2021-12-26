# spike-learn-nx

## Setup steps

```bash
npm install -g nx
```

### Setting up the workspace

```bash
yarn create nx-workspace
yarn create v1.22.5
[1/4] 🔍  Resolving packages...
[2/4] 🚚  Fetching packages...
[3/4] 🔗  Linking dependencies...
[4/4] 🔨  Building fresh packages...
success Installed "create-nx-workspace@13.4.1" with binaries:
      - create-nx-workspace
[###########################################################################] 193/193?✔ Workspace name (e.g., org name)     · spike-learn-nx
✔ What to create in the new workspace · apps
✔ Use Nx Cloud? (It's free and doesn't require registration.) · No

>  NX  Nx is creating your v13.4.1 workspace.

  To make sure the command works reliably in all environments, and that the preset is applied correctly,
  Nx will run "yarn install" several times. Please wait.

✔ Installing dependencies with yarn
✔ Nx has successfully created the workspace.

———————————————————————————————————————————————


>  NX   NOTE  First time using Nx? Check out this interactive Nx tutorial.

  https://nx.dev/getting-started/nx-core

✨  Done in 35.84s.
```

### Add Node generator

```bash
yarn add --dev @nrwl/node
```
