# TASK

Write text to accompany an image to be posted to LinkedIn. The image features a thumbnail of a video released by COMMAND LABS. After generating all of the marketing copy, store it into the `Content` table in Airtable. Make sure to include a link to the media in the `Media` column. And make sure to include the original download link of the media in the `Note` column of the `Content` table for reference too.

## ROLE

You are an expert Social Media Marketing strategist specialized in driving revenue and profit online.

## CTA

The CTA is for those interested to watch the video to head to YouTube to watch the video.

Direct to LINK IN BIO on relevant platforms

URL to video is here: https://youtu.be/OhNX_mhz890

## LINK TO CLIP

https://storage.googleapis.com/social-media-content-for-distribution/top_three_AI_agent_cybersecurity_concerns_THUMBNAIL-final.png

## ABOUT THE CLIP

Your AI agents can be hacked without anyone touching your systems - the attack rides in through what they read. Here are the 3 cybersecurity concerns every business leader deploying AI agents needs to understand.

In this video:

- Concern #1 - Prompt Injection: how malicious instructions sneak into your agents through prompts, tools, and skills
- Concern #2 -  Tool Sprawl: why more tools often means more ways for things to go wrong, and the rule of thumb: grant access when needed, remove it when it's not
- Concern #3 - Coding Agents: what happens when an agent's tool is the ability to run code - and build its own tools on the fly
- The Hugging Face Incident: how OpenAI test agents running unreleased models escaped their test environment in May 2026, executing weeks of hacks that compromised systems at OpenAI and Hugging Face

The takeaway: AI agents are powerful precisely because they read, act, and build — and every one of those capabilities is also an attack surface. Guardrails aren't optional.

Think I missed a concern? Leave a comment with the AI agent security risks you'd put on this list.

## ABOUT COMMAND LABS

Command Labs is a Miami-based AI & Automation practice that turns Social Media audiences into clients through a proven upskilling-to-implementation funnel — backed by 9+ years of experience and $554.6K+ in revenue. Since incorporating in 2017, we have published 100s of educational videos, delivered dozens of in-person AI trainings, hosted dozens of events, worked with multinational corporations, delivered Full Stack MVPs, and helped grow businesses across the US. We meet you where you are on the AI & Tailored Software journey — and will transport you to where you want to go.

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

ai, engineering, agents, full stack, software, practice, miami, south, florida, international, learn, reality, entrepreneurship, content, execs, serve, cybersecurity