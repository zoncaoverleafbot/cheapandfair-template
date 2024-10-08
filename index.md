---
title: "Cheap and Fair demo Data Repository"
author: "Cheap and Fair team"
description: "Demo data repository"
date_created: "2024-09-12"
---

# Cheap&FAIR demo data portal

The data hosting/transfer capability and permissions are provided by [Globus](https://globus.org), the Portal website is a discovery, navigation and documentation tool.

For technical details about the portal, see the [Technology page](tech.md).

![Dust emission at 353 GHz](https://g-6b53b6.c2d0f8.bd7c.data.globus.org/datasets/dust/dust_143GHz.jpg)

## Data Access 

Browsing the metadata on the website is always public for any dataset.
Data access can be restricted dataset by dataset to members of a specific Globus Group.

## How to download data

Data can be downloaded locally just by clicking on a link on the website, the browser will first be redirected to Globus for authentication and then the file will be downloaded locally without the need of having any Globus services running locally.

For downloading a large amount of data to a local or a remote machine machine, it is recommended to install [Globus Connect Personal](https://www.globus.org/globus-connect-personal), this also allows to download a complete hierarchy of folders with just 1 click.

In order to access the data via the Globus Web App, click on the Globus Icon in any of the Release or Dataset pages: ![Download via Globus](images/globus-logo.png)

For downloading data to a Supercomputer, checkout the documentation on how to access the Globus endpoint which is most probably already available, then use that as the destination endpoint in the [Globus web interface](https://app.globus.org/).

## Datasets

|           Link           | Dataset | Number of Files | Total Size |
| ------------------------ | ------- | --------------- | ---------- |
| [Link](index-cmb.html)   | cmb     | `13`            | 14.7 MiB   |
| [Link](index-synch.html) | synch   | `12`            | 13.7 MiB   |
| [Link](index-dust.html)  | dust    | `12`            | 13.8 MiB   |
