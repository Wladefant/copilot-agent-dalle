# DALL-E Chat Agent for GitHub Copilot Chat

This Visual Studio Code extension uses DALL-E 3 to generate images based on your prompts. It's integrated into GitHub Copilot Chat, providing a unique and fun way to visualize your ideas.

## Features

1. **Direct Prompts**: Write your prompt directly to get an image generated from DALL-E 3.

    ![Direct Prompt Example](./images/example2.png)

2. **Git Branch Names**: Use the `#git` variable to generate a prompt from your git branch name. This is especially fun with VS Code's randomly-generated branch names.

    ![Git Branch Name Example](./images/example3.png)

3. **Affirmations**: Use the slash command `/affirmation` to see an image of a cute animal who has looked at the changes in your workspace, and will tell you something nice about them!

    ![Affirmation Example](./images/example1.png)

## Configuration

To use this extension, you need to provide your OpenAI and Azure AI keys. These keys are used to make AI requests for generating images. You can enter these keys when prompted by the extension.

## Slash Commands

This extension provides the following slash commands:

- `/affirmation`: Generates an image of a cute animal with a positive affirmation.
- `/flow`: Visualize the code flow based for the current code
- `/render`: Preview the current code as website rendering based on the current code

