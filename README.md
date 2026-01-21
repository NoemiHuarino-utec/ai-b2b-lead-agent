# AI B2B Lead Qualification Agent

This project implements a generative AI agent designed to analyze unstructured B2B leads
and convert them into structured, CRM-ready insights.

## Problem
B2B teams receive leads from multiple channels in free-text format, making it hard
to prioritize and act on them efficiently.

## Solution
An event-driven workflow using n8n as an orchestrator and a generative AI agent
to classify intent, priority, pain points, and suggest next actions.

## Architecture
Webhook → n8n → AI Agent → Data Validation → Persistence (Supabase / Mock CRM)

## Tech Stack
- n8n (workflow orchestration)
- LLM (OpenAI-compatible)
- Supabase (data persistence) or Google Sheets (mock)
- REST APIs

## Status
Prototype / Proof of Concept
