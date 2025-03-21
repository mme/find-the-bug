# Find the bug

### Set up CopilotKit for development

(make sure you have pnpm and turbo installed)

In one terminal (keep it open), run:

```
cd CopilotKit/CopilotKit
pnpm i
turbo run dev
```

Wait for this to finish compiling.

Then, in aother terminal (keep this process running too):

```
cd CopilotKit/CopilotKit/examples/next-openai
pnpm run example-dev
```

### The bug

Go to: http://localhost:3000/find-the-bug

In the chat window, paste this:

```
navigate to /home and then alert the path
```

Observe that the path is updated, but CopilotKit doesn't alert the path.

This is hard - good luck!
