# Linea Token List - Development Guide

This document provides guidelines and steps for setting up, developing, and managing the Linea Token List project.

## Quick Start

### Configuration Setup

1. Duplicate the Configuration:

```bash
cp .env.template .env
```

2. API Key Setup:

Modify `.env` and substitute `<YOUR_INFURA_API_KEY>` with your actual Infura API Key.

### Dependency Installation

Install all the necessary packages via:

```bash
npm i
```

### Scripts Execution

<b>Verify mainnet shortlist</b>

Run the production script with:

```bash
npm run verify
```

## Unit tests

To perform unit tests, execute:

```bash
npm run test
```

## Lint

To perform lint, execute:

```bash
npm run lint
```

## Managing GitHub Page

The GitHub page content is generated using [index.html](../index.html).

Use the `Live Server` extension in Visual Studio Code to preview this page.
