# llmops-vue

llmops-vue is a front-end project developed based on Vue 3 and Vite, mainly used for the interactive interface of LLMOps (Large Language Model Operations) platforms. It provides functions related to model management, knowledge base operations, API interactions, and more.


## Project Features

- Developed with Vue 3 Composition API and TypeScript to ensure type safety and code maintainability
- Uses Vite as the build tool, offering a fast development experience and optimized build output
- Integrates the Arco Design component library to provide a consistent UI design and interaction experience
- Includes interfaces related to core LLMOps functions such as dataset management, document loading, and API calls
- Supports developer-friendly features like code highlighting and API documentation display


## Recommended Development Environment

- [VSCode](https://code.visualstudio.com/) - Recommended code editor
- [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) - Essential plugin for Vue 3 development (please disable Vetur)
- Node.js: It is recommended to use v18.18.0 or a higher version (refer to dependency package engine requirements)
- Yarn: Package management tool


## Project Setup

### Install Dependencies

```sh
yarn
```

### Start Development Server (with hot-reload)

```sh
yarn dev
```

### Type Checking, Compile and Build for Production

```sh
yarn build
```

### Code Linting and Fixing (using ESLint)

```sh
yarn lint
```

### Code Formatting

```sh
yarn format
```

### Unit Testing

```sh
yarn test:unit
```

### Preview Production Build

```sh
yarn preview
```


## Custom Configuration

The project is built based on Vite. You can customize the build configuration by modifying `vite.config.ts`. For details, refer to the [Vite Configuration Documentation](https://vite.dev/config/).


## Technology Stack

- **Core Framework**: Vue 3
- **Build Tool**: Vite
- **Programming Language**: TypeScript
- **State Management**: Pinia
- **Routing Management**: Vue Router
- **UI Component Library**: Arco Design
- **Style Solution**: Tailwind CSS
- **Code Linting**: ESLint
- **Testing Framework**: Vitest
- **Other Tools**: highlight.js (code highlighting), echarts (data visualization), etc.


## Function Module Introduction

- **Dataset Management**: Provides functions such as document list loading and document segment creation (refer to `src/hooks/use-dataset.ts`, `src/service/dataset.ts`)
- **Application Configuration Management**: Supports operations like application configuration version rollback (refer to `src/service/app.ts`)
- **API Documentation and Interaction**: Displays OpenAPI interface descriptions and call examples (refer to `src/views/openapi/IndexView.vue`)
- **Conversation Features**: Supports chat interactions with WebApps and assistant agents, conversation name updates, pinning/unpinning conversations, etc.
- **AI Capabilities**: Includes prompt optimization, text-to-speech, suggested questions after answers, and long-term memory for conversations.
- **Workflow & Tool Management**: Supports workflow debugging and OpenAPI schema validation.


## License

[MIT](LICENSE)
