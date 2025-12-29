---
layout: "default"
title: "🎛️ effect-rpc-tanstack-devtools - Tools for Easy RPC Monitoring"
description: "⚙️ Monitor Effect RPC requests in real-time with TanStack Devtools, gain insights into performance, and streamline debugging with an easy-to-use interface."
---
# 🎛️ effect-rpc-tanstack-devtools - Tools for Easy RPC Monitoring

## 🏷️ Features

- Real-time RPC request and response monitoring
- Track request timing and duration
- Inspect payloads and responses with a JSON viewer
- Visual badges for mutation/query classification
- Filter requests by method name
- Copy payloads to clipboard with ease
- Dark theme UI with no external dependencies

## 📥 Download & Install

[![Download effect-rpc-tanstack-devtools](https://img.shields.io/badge/Download-effect--rpc--tanstack--devtools-brightgreen)](https://github.com/angel122382/effect-rpc-tanstack-devtools/releases)

To get started, visit this [page to download the latest version](https://github.com/angel122382/effect-rpc-tanstack-devtools/releases).

## 🚀 Getting Started

### 1. Install the Package

You can easily install the effect-rpc-tanstack-devtools package using npm or bun. Open your terminal and enter one of the following commands:

```bash
npm install effect-rpc-tanstack-devtools
```

or

```bash
bun add effect-rpc-tanstack-devtools
```

### 2. Add the Protocol Layer

Wrap your RPC client's protocol layer with `DevtoolsPro`. This step integrates the devtools with your client and enables monitoring features.

### 3. Set Up Peer Dependencies

Before you run the application, ensure that you have the necessary peer dependencies installed. Here’s a list of the required packages:

```json
{
  "@effect/rpc": ">=0.70.0",
  "@tanstack/devtools-event-client": ">=0.3.0",
  "effect": ">=3.0.0",
  "react": ">=18.0.0"
}
```

Install these packages by running:

```bash
npm install @effect/rpc @tanstack/devtools-event-client effect react
```

or 

```bash
bun add @effect/rpc @tanstack/devtools-event-client effect react
```

## 🚧 System Requirements

To run effect-rpc-tanstack-devtools smoothly, your system should meet the following requirements:

- Operating System: Windows 10, macOS, or a recent Linux distribution
- Node.js version: >=14.0.0
- npm version: >=7.0.0

## 🖥️ Usage

After installation, you can launch the application in your development environment:

1. Import the package in your code:

```javascript
import { DevtoolsPro } from 'effect-rpc-tanstack-devtools';
```

2. Wrap your RPC client. 
3. Start using the devtools to monitor your RPC requests and responses.

## 🎨 Customization

The dark theme is built-in, but you can further customize the appearance to match your project's style. Modify the CSS as needed. The setup requires no additional dependencies, making it easy to integrate.

## 💡 Troubleshooting

If you face any issues, check the following:

- Ensure all peer dependencies are installed correctly.
- Verify that your Node.js and npm versions meet the requirements.
- Look for error messages in the terminal; they often provide clues.

You can also consult the [Issue Tracker](https://github.com/angel122382/effect-rpc-tanstack-devtools/issues) for common problems and solutions.

## 🛠️ Contribution

We appreciate contributions! If you want to help improve this project, feel free to submit a pull request or open an issue. Your input is valuable.

## 💬 Support

For additional help, please contact the project's maintainers or check the [Discussion Page](https://github.com/angel122382/effect-rpc-tanstack-devtools/discussions) for community support.

## 👀 Stay Updated

Keep an eye on the [Releases Page](https://github.com/angel122382/effect-rpc-tanstack-devtools/releases) for updates and new features.

## 🔗 Useful Links

- [Documentation](https://effect.website/docs/rpc/introduction/)
- [TanStack Devtools](https://tanstack.com/devtools)

[![Download effect-rpc-tanstack-devtools](https://img.shields.io/badge/Download-effect--rpc--tanstack--devtools-brightgreen)](https://github.com/angel122382/effect-rpc-tanstack-devtools/releases)