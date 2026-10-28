# Promptline

AI-assisted runtime configuration changes, with validation and explicit confirmation.

## About the project

A configuration change can involve checks, approval and coordination across services. Promptline brings those steps into a backend that validates a proposal and asks for confirmation before execution.

## My work

I built the Spring-based backend for proposing configuration changes, tracking plans and reporting execution progress. Defined tools connect that flow to configuration checks and pull-request workflows. The emphasis is on making the proposed change and its execution state clear throughout the process.

## Architecture

- **Java and Spring Boot** handle backend APIs, plans and confirmation.
- **MCP tools and Git** connect configuration checks with pull-request coordination.
- **AWS Lambda/API Gateway and S3** support the wider configuration architecture.

## Current status

I keep the application code private. This repository is a written project overview, and the portfolio page explains the backend and architecture.

[Read the portfolio overview](https://portfolio.puranjay-mishra.workers.dev/projects/promptline/)
