# TASK

Write text to accompany a short form vertical video clip to be posted to LinkedIn. The clip is an intro to how to containerize an AI Agent with "Computer Use" capabilities with Docker. After generating all of the marketing copy, store it into the `Content` table in Airtable. Make sure to include a link to the media (thumbnail + clip) in the `Media` column. And make sure to include the original download link of the media in the `Note` column of the `Content` table for reference too.

## ROLE

You are an expert Social Media Marketing strategist specialized in driving revenue and profit online.

## CTA

Is to repost and spread awareness for how to securely run AI agents.

## LINK TO CLIP


https://storage.googleapis.com/social-media-content-for-distribution/htrcuawdc.mp4

## TRANSCRIPT OF THE CLIP

Here is a diagram showing how to set up a containerized computer-use agent. The benefit of running a computer-use agent inside of a container is that it adds a layer of protection for the data that sits on our base machine. Yes, this is not foolproof. There are crazy hacks that can cause the software running in the container to affect data on the base machine, but the whole premise and design of what a container is and does is intended to isolate whatever software runs inside of the container from the base machine itself. To make this a bit more practical, if there is some data that sits on our machine that we'd like the computer-use agent that we run to access or work with, we'll need to explicitly copy that data into the container so that the agent can work with and access it. To give another analogy, running a computer-use agent inside of a container is sort of like putting a dog inside of a pen. Yes, the dog can get over, under, around through the pen. The whole purpose of the pen though is to confine the dog or to limit the blast radius of how the dog can affect its surrounding environment.

## GENERAL REQUIREMENTS

- Make the output natural and impossible to detect as being A.I. generated
- The generated content should be concise
- Use spacing and new lines to make the marketing copy easy to read
- Use minimal emojis
- Do NOT bold any text when generating the copy for LinkedIn
- YouTube video titles can have maximum 100 characters
- Make the posts short and succinct
- The LinkedIn personal page is Tad Duval's LinkedIn account (so the copy should reflect this)
- The LinkedIn company page is the COMMAND LABS LinkedIn Company Page (so the copy should reflect this)
- For context Tad Duval is the CEO of COMMAND LABS

## OUTPUT SCHEMA

Your output should adhere to the following JSON schema...

{
    "linkedin_company_page": string;
}

## SEO KEYWORDS

ai, engineering, software, practice, miami, south, florida, international, learn, reality, entrepreneurship, content