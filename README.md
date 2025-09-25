# Episode #1 Generating Documentation

In the premiere episode, Carl Franklin and Jeff Fritz generate a user manual for an existing website using the GitHub Copilot Agent.

YouTube Video: https://youtu.be/RewtTswNdHY

Code it with AI Home Page: https://codeitwithai.com

----

We learned about [CopilotThatJawn.com](CopilotThatJawn.com) a website Jeff wrote and manages that delivers tips and tricks for working with Copilot.  Jeff showed us an example of [using Copilot with the Playwright MCP](https://copilotthatjawn.com/tips/generate-user-manuals-with-copilot-playwright.md) to create a user manual for a website.

> An **MCP Server** is a small service that runs on your machine and makes a series of APIs available to the AI Large Language Model to interact with. 

Steps to get started and build your user manual:
1. [Install the Playwright MCP](https://github.com/microsoft/playwright-mcp)

   Make sure you [install Node](https://nodejs.org) if you don't already have it installed because the Playwright MCP is delivered as a Node service.  Debbie O'Brien has a [great video](https://www.youtube.com/watch?v=exsikHe20D8) to help you get started with the tools
   
3. While in Agent mode, use a prompt similar to the following:
  ```code
  I need to document [specific workflow/feature] at [URL] with screenshots. 

  Take the following steps:
  1. Navigate to the relevant pages
  2. Fill in sample data where needed
  3. Capture screenshots at key interaction points
  4. Save images with descriptive filenames
  
  The workflow involves: [describe the user journey]

  Publish your manual to the [folder location] folder with name [document name]
  ```

More ideas and samples are available on the [original CopilotThatJawn article](https://copilotthatjawn.com/tips/generate-user-manuals-with-copilot-playwright.md)

You can see our [demo user-documentation for the CopilotThatJawn website](https://github.com/csharpfritz/CopilotThatJawn/tree/main/user-docs) on GitHub.
