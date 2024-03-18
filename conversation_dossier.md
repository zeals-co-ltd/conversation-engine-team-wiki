# Conversation Dossier (CD)
<p align="center">
    [![CI/CD Workflow](https://github.com/zeals-co-ltd/journey/actions/workflows/cicd.yml/badge.svg)](https://github.com/zeals-co-ltd/journey/actions/workflows/cicd.yml)
    <a href="https://github.com/zeals-co-ltd/conversation-dossier" alt="Repo">
        <img src="https://badgen.net/static/repo/conversation-dossier/green?icon=github" /></a>
    <a href="https://github.com/zeals-co-ltd/zero-api/tree/master/content/02_domains/conversation_dossier" alt="Docs">
        <img src="https://badgen.net/static/repo/docs/cyan?icon=github" /></a>
    <a href="https://github.com/zeals-co-ltd/conversation-dossier" alt="Converage">
        <img src="https://github.com/zeals-co-ltd/conversation-dossier/blob/feat/ZMT-1066-rename-step/.badges/coverage.svg" /></a>
</p>

## TL;DR
This service is responsible for:
- Receiving event for event router
- Handling usecase of that event (for example RawFreeText may be human support request, component ID message, image map reply, etc.)
- After determening the usecase, sending command to Conversation Dossier to extract & deliver components of said usecase.
- Storing conversation history between bots & end users.
