﻿# Video Game Database App

A lightweight web application for uploading and searching video game data.

---

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Backend (AWS Lambda)](#backend-aws-lambda)

---

## Overview

The Video Game Database App allows you to:

- **Upload Game Data:** Input one or more game entries in JSON format.
- **Search Game Data:** Filter games by **Platform**, **Genre**, or **Year**.
- **View Results:** Browse search results with built-in pagination.

The frontend is built using **HTML**, **Bootstrap**, and **jQuery**, while the backend is powered by an **AWS Lambda function** (written in Python) that manages data storage and queries.

You can view the app online at [[[https://chrishiggins.dev/VideoGameDB/](https://chrishiggins.dev/VideoGameDB/)].

---

## Installation

1. **Clone or Download** this repository.
2. Open `index.html` in your browser.

---

## Usage

- **Uploading Data:**  
  Paste your JSON data into the textarea and click the **Upload Game Data** button.

- **Searching Data:**  
  Select a filter from the dropdown menus and click the **Search** button to view matching game records.

---

## Backend (AWS Lambda)

The AWS Lambda function (written in Python) handles:
- Inserting single or multiple game data entries.
- Fetching unique values for the filters.
- Querying the game database.
⌢嘠摩潥慇敭䉄•਍
