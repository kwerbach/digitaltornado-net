# CLAUDE.md — digitaltornado.net

## Project Overview

**Repository:** `kwerbach/digitaltornado-net`
**Live URL:** https://digitaltornado.net
**Hosting:** Pair Networks shared hosting, user `kwerbach`
**Deploy target:** `~/public_html/digitaltornado.net/`

## Architecture

Static HTML site. No build step. Historical site for the "After the Digital Tornado" conference (Wharton, November 2017) and edited volume (Cambridge University Press, 2020).

## Deployment

Push to `main` triggers GitHub Actions rsync to Pair Networks.
