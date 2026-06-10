# novakuapp.github.io

Root site for the **NovakuApp** GitHub organization.

Served at: `https://novakuapp.github.io/`

## Purpose

This repository exists to host root-level files required by ad networks, app stores, and verification services. Legal documents live in a separate repo (`NovakuApp/legal`) served at `https://novakuapp.github.io/legal/`.

## Contents

- `app-ads.txt` — IAB Tech Lab spec, authorizes Google AdMob (publisher `pub-8503708244413209`) as a direct seller for all NOVAKU mobile apps. Required by AdMob for app verification and matched-demand serving.

## Adding new authorized sellers

If we ever onboard a mediation partner (Meta Audience Network, AppLovin, Unity Ads, etc.), append one line per partner per their certification ID. Format: `domain, publisher_id, relationship, certification_id`.
