https://www.contributor-covenant.org/version/1/4/code-of-conduct/

when using AGI.zip, you can ask it to, periodically, drop a .zip file containing it's memory and skills contents. It has a sandbox environment to execute code in, but the container is isolated, so only scripts that work within it's local environment can be executed by the gpt itself.

until we get the openGPTs version, an interim step is using the repl.it mobile app (or website) to run code on your local device. You can ask the gpt to deliver scripts it's written as .zip files.

This repository is intended as a community resource to store these generated zip files.

---
When adding your contribution:

-Create a folder with your handle in the AGI folder, Skills folder, or Outputs folder

-Create a subfolder with a descriptive name for the contents of the .zip file you're uploading

In that subfolder, include:
a .zip file

a README describing the contents of the zip file as follows:

if in the AGI folder, a list of the GPT's current Skills in that Readme (you can ask it to print this for you), or any Memories you might want to make someone else aware of

if in the Skills folder, a natural language description of the Skill (ideally with example use-cases)

if in the Outputs folder, a README for the collection of files in the .zip file (and their intended use-cases). for Outputs, ask AGI.zip to include the appropriate .repl file in the zip of filesit gives you, such that each .zip can be deployed to replit easily.
---

GPT code outputs can be unreliable -- if you don't understand the code you're looking at upon unzipping the file, don't run it. Best case, it errors out, worst case, it's malware. I'll try to keep an eye out for this. If you're not sure, upload the .zip to agi.zip and ask it to check the contents before running it on repl.it.

Future plans would be to run this via opengpts, deploy it as a [Commune](https://github.com/commune-ai/commune) module in the event you'd like to monetize your iteration/configuration, and add more ways to collaborate & exit from the OpenAI platform lock.
Contact @yikesawjeez on Twitter if you'd like to help maintain!
