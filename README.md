This is very much a work in progress. Features **will** change over time.

[![codecov](https://codecov.io/gl/Sood/vgstation-statistics/branch/master/graph/badge.svg)](https://codecov.io/gl/Sood/vgstation-statistics)
[![gitlabci](https://gitlab.com/Sood/vgstation-statistics/badges/master/build.svg)](https://gitlab.com/Sood/vgstation-statistics/pipelines)

# Statistics viewer for /vg/station
This is a statistics viewer which parses the statfiles exported from /vg/station rounds and writes them to db, then displays them in such a way that people can actually UNDERSTAND THEM WOW

Anyone who wants to help out or call my code shit is more than welcome. I'd like to catch any issuse with this before they become real issues. This is the first project of this nature I have undertaken (in Python at least) and I am completely amateur.

# Prereqs
Should be satisfied by the requirements.txt.

Python, Flask, Flask-SQLAlchemy, Requests

# Setup
`pip install -r requirements.txt`

Modify config.py as needed.

While in the venv, run:
python db_create.py
