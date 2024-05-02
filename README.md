# Why use NPM workspaces?

1. NPM workspaces are simple in implementation and work perfectly well out of the box, since in this project we already use NPM as our package manager.
2. Tools like Nx and TurboRepo are for more advanced and big projects, at this point to not overcomplicate the state the decision was made to utilize this solution.
3. It is easy to migrate to TurboRepo from NPM workspaces in case the project will need more scalability and advanced functionality.

# Core Commands for Managing NPM Workspaces

#### Install package for specific workspace
```bash
npm install <package-name> --workspace=<workspace-name>
```

#### Run command for all workspaces
```bash
npm run test --workspaces --if-present
```


