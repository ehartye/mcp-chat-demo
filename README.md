# MCP Chat Demo

A sample chat application demonstrating integration with Model Context Protocol (MCP) servers.

## Project Structure

```
mcp-chat-demo/
├── package.json
├── README.md
├── .gitignore
├── src/
│   ├── App.tsx
│   ├── main.tsx
│   ├── components/
│   │   ├── Chat.tsx
│   │   ├── MessageList.tsx
│   │   ├── MessageInput.tsx
│   │   └── MCPConnection.tsx
│   ├── lib/
│   │   ├── mcp-client.ts
│   │   └── types.ts
│   └── styles/
│       └── main.css
└── public/
    └── index.html
```

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/mcp-chat-demo.git
cd mcp-chat-demo
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## Features

- Connect to local or remote MCP servers
- Real-time chat interface
- Support for MCP tools and resources
- Message history
- Error handling and reconnection logic

## Technology Stack

- React 18
- TypeScript
- Vite
- TailwindCSS
- MCP TypeScript SDK