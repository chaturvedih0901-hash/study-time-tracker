2. readme.md

# Study Time Tracker

## Overview
The Study Time Tracker is a modular Python-based Command Line Interface (CLI) application designed to enhance student productivity. It allows users to start and stop study sessions, automatically calculates time elapsed, tracks progress against a custom daily goal, and generates detailed subject-wise and weekly reports. Data persistence is managed seamlessly via local JSON storage.

## Features
- **Start/Stop Study Sessions:** Log real-time study sessions with subject names and specific topics.
- **Daily Progress & Goal Tracking:** Set a target daily study duration and track real-time progress percentages.
- **Subject-Wise Analytics:** Aggregate total time spent and total session counts per subject.
- **Weekly Productivity Reports:** Review total study time and progress trends over the past 7 days.
- **Session History:** Access a structured historical log of all past study sessions.
- **JSON File Persistence:** Automatic reading and writing to local JSON storage (`sessions.json`).
- **Input Validation:** Built-in safeguards preventing dual active sessions and bad menu inputs.

## Technologies Used
- **Language:** Python 3.x
- **Storage:** JSON (Standard Library)
- **Built-in Modules:** `datetime`, `json`, `unittest`
- **Environment:** VS Code / Terminal

## File Structure