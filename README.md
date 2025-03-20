# Find the bug

### Set up CopilotKit for development

(make sure you have pnpm and turbo installed)

In one terminal (keep it open), run:

```
cd CopilotKit/CopilotKit
pnpm i
turbo run dev
```

In the other terminal (keep this process running):

```
cd CopilotKit/CopilotKit/examples/next-openai
pnpm i
pnpm run example-dev
```

### The bug

In the chat window, paste this:

```
navigate to /home and then alert the path
```

Observe that the path is updated, but CopilotKit doesn't alert the path.

This is hard - good luck!
