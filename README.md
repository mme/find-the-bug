# Find the bug - Hard Mode

### Set up CopilotKit for development

(make sure you have pnpm and turbo installed)

```
cd CopilotKit/CopilotKit
pnpm i
pnpm -w freshbuild
turbo link:global
turbo run dev
```

### Set up the demo app for development

```
cd my-app
pnpm i
pnpm link --global @copilotkit/react-ui @copilotkit/react-core @copilotkit/runtime-client-gql @copilotkit/shared @copilotkit/runtime
pnpm run dev
```

### The bug

In the chat window, paste this:

```
navigate to /home and then alert the path
```

Observe that the path is updated, but CopilotKit doesn't alert the path.

Good luck!
