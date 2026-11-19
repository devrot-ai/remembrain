# Remembrain

A simple tool that helps people with dementia recognize the people around them. It uses a webcam to detect faces, match them against a list of known people, and show a reminder on screen with the person's name and relationship.

## Why It Exists

Dementia makes it hard to remember faces. Even a small prompt like "This is Rohit. He is your nephew." can make a big difference. This project explores whether a webcam and face recognition can help in a simple way.

## How It Works

The webcam captures faces. The system converts them into numbers, compares those numbers to stored faces, and if it finds a match, it shows you who the person is. It can also read the reminder out loud.

## Getting Started

You need Python 3.10 or 3.11.

`ash
py -3.11 -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python main.py
`

Add photos of people you want to recognize in the aces/ folder and their details in data/people.json.

## What You Get

Real-time face detection from your webcam. Recognition of stored faces. On-screen reminders with name and relationship. Optional voice reminders. Location tracking with Google Maps.
