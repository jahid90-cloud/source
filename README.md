# Source Service

A service to manage source control repositories

- Tracks commits across the registered git repositories
- Provides pub-sub mechanism to observe repositories
- Serves as input to builder
- Has a read-only view of the repositories; enforced via a read-only filesystem

