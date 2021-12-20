There are three ways to specify npm dependencies in package.json: dependencies, devDependencies, and peerDependencies. Production and dev dependencies are familiar to most developers and their resolution is intuitive. NPM can resolve multiple versions of dependencies; if two dependencies require different versions of the same package, NPM can download both of them.

peerDependencies are used less frequently and have a less obvious resolution.

Most projects include hundreds of dependencies making it difficult to analyze changes to the node_modules directory and lock file. Working with a few dependencies in a controlled sandbox can make this a lot easier.

To demonstrate how peerDependencies are resolved and how they are different from dev and production dependencies, this example will include a parent app, a dependency, a shared dependency, and a peer dependency.

## dependencies

- https://www.npmjs.com/package/@spake/npm-demo-dependency  
- https://www.npmjs.com/package/@spake/npm-demo-shared-dependency  
- https://www.npmjs.com/package/@spake/npm-demo-peer-dependency
