## Dev kit

### What is Dev kit?

Dev kit is a start-kit which intends to make building dev tools with GUI easier.

### Why?

I experiement with different ideas to make programming fun and easy. As a result, I build tools that would help me be more productive and hopfully help others as well. [Majestic](https://github.com/Raathigesh/majestic/) is one of those.

I used to use electron to build these tools but I wanted to find a more suitable tech stack and eventually move away from electron. So I started re-writing [majestic](https://github.com/Raathigesh/majestic/tree/next) without electron but with a node server. So users can install the module globally and start using it. Recently [reactotron](https://github.com/infinitered/reactotron/issues/782) also made the same decision.

So instead of setting up the boilerplate everytime I build a tool, this starter kit could ease things a bit.

Dev kit comes with

- A webpack config for React and Typescript for frontend
- A node server with typescript support for backend
- GraphQL support for communicating with UI and the server
- Nodemon config for the server
- VS Code task to debug the server when you have to

## Scripts

- `ui`: Starts the webpack dev server and serves the UI
- `build-ui`: Builds the UI project
- `debug`: Runs the node server via nodemon in watch mode
- `build-server`: Builds the node server
- `prod`: Builds both the UI and the server
