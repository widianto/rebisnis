# rebisnis

A simple bash script to produce a single compact PDF file of Bisnis ePaper edition.

This script will do three things: combine PDF (merge) into single one, compact PDF file using GhostScript, and remove remaning old PDF files to your home trash.

### Requirements

* Mac system
* Bisnis PDF file (eg: Edisi_Harian_2020-08-28_5.pdf or Edisi_Weekend_2020-08-16_10.pdf)
* Automator Combine PDF Script on ``/System/Library/Automator/Combine\ PDF\ Pages.action/Contents/Resources/join.py``
* GhostScript (use homebrew -> ``brew install ghostscript``)

### Installation

* Clone/download and make sure the script executeable

### How To Use

``rebisnis 2020-08-29 Harian``
``rebisnis 2020-08-29 Weekend``

This program will produce a single "Harian_2020-08-16_Weekend.pdf" or "Harian_2020-08-15.pdf" for your archival"

### TODO

Automate the download process, eh?

