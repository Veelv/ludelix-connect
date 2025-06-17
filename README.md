# Ludelix Connect

Ludelix Connect is a JavaScript/TypeScript library designed to bridge the gap between your frontend application and the Ludelix Framework backend, similar to how Inertia.js operates. It aims to provide a seamless experience for building single-page applications (SPAs) with a traditional server-side routing approach.

## Features

- **Seamless Integration:** Connects directly with the Ludelix Framework.
- **Frontend Adapters:** Provides adapters for popular frontend frameworks like React, Vue, and Svelte.
- **Form Handling:** Simplified form submission and data handling.
- **WebSocket Support:** Real-time communication capabilities.
- **Utility Functions:** Common utility functions to streamline development.

## Installation

To install Ludelix Connect in your project, use npm or yarn:

```bash
npm install ludelix-connect
# or
yarn add ludelix-connect
```

## Usage

### Basic Initialization

```typescript
import { connect } from "ludelix-connect";

connect();
```

### React Adapter Example

```typescript
import React from "react";
import { useLudelix } from "ludelix-connect/adapters/react";

function MyComponent() {
  useLudelix();
  return <div>Hello Ludelix!</div>;
}

export default MyComponent;
```

### Form Handling Example

```typescript
import { LudelixForm } from "ludelix-connect";

const form = new LudelixForm();
// Use form methods for submission, data handling, etc.
```

## Development

To set up the development environment for Ludelix Connect:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Veelv/ludelix-connect.git
    cd ludelix-connect
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Run tests:**

    ```bash
    npm test
    ```

4.  **Build the project:**

    ```bash
    npm run build
    ```

## Contributing

We welcome contributions to Ludelix Connect! Please see the `CONTRIBUTING.md` file for guidelines on how to contribute.

## License

Ludelix Connect is open-source software licensed under the MIT License. See the `LICENSE` file for more details.


