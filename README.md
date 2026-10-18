# Ollama NDJSON Stream Reconstruction Answer

This folder contains `public/answer.json`, the raw JSON response for the exam grader.

## Deploy as a public static file on Vercel

1. Extract this ZIP.
2. In PowerShell, change directory to this folder:
   `cd path\to\ollama-stream-answer`
3. Log in if needed: `vercel login`
4. Deploy the static directory:
   `vercel --prod`
5. If Vercel asks for a project setup, follow its prompts. Make sure deployment protection is disabled so the grader can fetch it without authentication.
6. Test the final URL by appending `/answer.json` to the production domain. The response must be raw JSON, not an HTML page.

The exact URL is created by your Vercel account at deployment time; it cannot be known before deployment.
