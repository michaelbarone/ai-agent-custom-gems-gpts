# ai-agent-custom-gems-gpts
customized gems and gpts for specific functions

Each folder contains a gem or gpt that is customized for a specific function.

Each folder should follow the following structure:

```
<folder>
  agent-prompt.md
  templates.md
```

Use the Template folder as a base to copy and paste to create a new custom gem or gpt.

## Creating Custom Gemini Gems and GPT templates in this repository

1. Create a new folder with the desired gem/gpt name
2. Copy the contents from the Template folder into the new folder
3. Edit `agent-prompt.md` to define the gem/gpt's core instructions and behavior
4. Modify `templates.md` to include any specialized templates or formats the gem/gpt requires

Always test and refine

5. Test the gem/gpt by uploading to Gemini Advanced
6. Refine the prompts based on testing results
7. Update the agent-prompt.md and templates.md with improvements found during testing


## Implementation on AI Platforms

### Implementing in Gemini Advanced

1. Visit [Gemini Advanced](https://gemini.google.com/advanced)
2. Click on "Gems" in the left sidebar
3. Select "Create a Gem"
4. Name the Gem and provide a description
5. In the "Instructions" section, copy and paste the contents of the `agent-prompt.md` file
6. Upload the `templates.md` and any other necessary knowledge files if the Gem requires specific data
7. Save and test the Gem

### Implementing in ChatGPT

1. Visit [ChatGPT](https://chat.openai.com/)
2. Click on "Explore GPTs" or "Create a GPT"
3. Select "Create" to build a new GPT
4. In the GPT Builder interface, click on "Configure"
5. Under "Instructions", copy and paste the contents of the `agent-prompt.md` file
6. For specialized templates, include them in the instructions or as separate knowledge files
7. Configure additional capabilities (web browsing, DALL-E, code interpreter) as needed
8. Test the GPT in the preview panel
9. When satisfied, click "Save" and publish the GPT (private or public)

Remember to update the local files with any improvements made during the online configuration process.

## Using Custom Gems and GPTs

### Common Commands

Most custom Gems and GPTs in this repository respond to these standard commands:

1. `/help` - Display available commands and capabilities for the specific gem/gpt
2. `/doc-out` - Output the full document being discussed or refined, untruncated
3. `/tasks` - List the tasks available to the current agent, along with descriptions
4. `/refine` - Refine a document based on user request, optionally targeting a specific section
5. `/yolo` - Toggle YOLO mode (available in some agents) for faster, less interactive processing

### Effective Interaction Techniques

For optimal results when using these custom Gems and GPTs:

1. **Clear Initial Prompts** - Begin with a specific request that outlines your goal:
   - "I need to create a marketing campaign for a new fitness product"
   - "Help me analyze this dataset to identify customer trends"

2. **Use Context Setting** - Provide relevant background information:
   - "I'm working with a B2B SaaS company targeting small businesses"
   - "This is for an academic research paper on climate change"

3. **Leverage Templates** - Request specific templates when available:
   - "Use the SWOT analysis template for my business idea"
   - "Apply the bug report template to document this issue"

4. **Iterative Refinement** - Start broad and refine through conversation:
   - Begin with: "Help me draft a business proposal"
   - Then refine: "Now focus on the financial projections section"

5. **Mode Selection** - Choose between interactive or YOLO mode when available:
   - Interactive mode: Step-by-step guidance through each section
   - YOLO mode: Generate complete output with minimal interaction

Remember that each custom Gem/GPT may have specialized capabilities based on its purpose. Check the specific folder documentation for unique features and commands.
