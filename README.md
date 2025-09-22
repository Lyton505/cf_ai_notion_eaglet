<div align="center">

# cf_ai_notion_eaglet  

AI interface for Notion internship tracker on Cloudflare

**Completion status:** not started • **ETA:** September 24, 2025

</div>

This project is currently in the planning phase. The following sections outline the intended features and goals.

## Overview

A minimal AI interface over my Notion internship tracker database comprising of application dates. It answers natural-language questions like “When did I apply to Asana?” or “What’s the stage for Google SWE?” by turning the question into a structured query, fetching the matching row(s) from Notion, and returning a concise answer plus the relevant fields.

## Tech stack

- Cloudflare Workers + Workers AI
- Durable Objects for session memory
- Cloudflare Pages (vanilla HTML/JS chat)
- Notion API
