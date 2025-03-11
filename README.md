<p align="center">
<img src="https://github.com/user-attachments/assets/bebd92b8-765e-4d63-bb3d-47e1bb8b51ad" width=500px>
</p>
<h1 align=center>Timeline Card</h1>
<p align=center>
<img src=https://img.shields.io/badge/HACS-Custom-orange.svg>
<img src=https://img.shields.io/badge/version-1.4.0-blue>
<img src="https://img.shields.io/maintenance/yes/2025.svg">
<img alt="Issues" src="https://img.shields.io/github/issues/valentinfrlch/llmvision-card?color=0088ff"/>
<img alt="Static Badge" src="https://img.shields.io/badge/support-buymeacoffee?logo=buymeacoffee&logoColor=black&color=%23FFDD00&link=https%3A%2F%2Fbuymeacoffee.com%2Fvalentinfrlch">
    <p align=center style="font-weight:bold">
      Custom Card to display the LLM Vision Timeline on your Home Assistant Dashboard in Danish
    </p>
</p>

  <p align="center">
    <a href="#prerequisites">🌟 Prerequisites </a>
    ·
    <a href="#installation">⬇️ Installation</a>
    ·
    <a href="#setup">🚧 Setup</a>
    ·
    <a href="#configuration">🔧 Configuration</a>    
  </p>
<p align="center">
  <a href="https://llmvision.org"> Visit Website →</a>
    </p>

<img src="https://github.com/user-attachments/assets/97f6e608-bdf3-44d1-89f1-fd89cda7b764" data-canonical-src="https://gyazo.com/eb5c5741b6a9a16c692170a41a49c858.png" width="50%" height="auto" />

## Prerequisites
1. LLM Vision and at least one AI provider set up
2. Timeline provider set up in LLM Vision
3. Blueprint or Automation to add events to the timeline

## Documentation
<a href="https://llm-vision.gitbook.io/getting-started/setup/timeline-card-beta"><img src="https://img.shields.io/badge/Documentation-blue?style=for-the-badge&logo=gitbook&logoColor=white&color=18bcf2"/> </a>

## Installation
Add the url of this repository to the custom respositories list in HACS.

## Setup
1. Install the card through HACS
2. Reload
3. Add the card to your dashboard

## Configuration

| Parameter         | Description                                                                              | Default                      |
|-------------------|------------------------------------------------------------------------------------------|------------------------------|
| number_of_events  | How many events to show                                                                  | 5                            |
| calendar_entity   | LLM Vision Timeline Entity (needs to be set up in LLM Vision Settings first)             | calendar.llm_vision_timeline |
| refresh_interval  | Refresh Interval (in seconds)                                                            | 10                           |
| language          | Language used to generate icons                                                          | en                           |
