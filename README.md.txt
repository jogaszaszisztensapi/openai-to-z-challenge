# Archaeologist Assistant – AI-Powered Archaeological Discovery Tool

## Project Objective
The goal of the Archaeologist Assistant is to function as an AI-based system capable of reasoning like a field archaeologist and identifying potential ancient sites in the Amazon region based on open-source data. The system integrates historical reports, LIDAR-based mapping data, and indigenous legends to provide location-based hypotheses with precise coordinates worth further exploration.

## AI Model & Technical Background
The system uses OpenAI’s GPT-4o-mini (o4-mini) language model, fully compliant with the OpenAI to Z Challenge requirements. It operates in the backend of the WordPress-based Napi Plusz website, powered by the AI Engine Pro plugin and enhanced with real-time WebSearch integration.
This allows the Archaeologist Assistant to access and analyze public online data sources. Upon user request, the AI processes data from:
- public LIDAR maps
- historical sources
- satellite imagery and indigenous legends

## AI Response Summary – Suggested Location
Suggested site: Mapinguari River, Brazil  
Coordinates: Latitude: -7.5, Longitude: -63.5

## Data Sources
1. https://portal.opentopography.org/datasets  
2. http://terrabrasilis.dpi.inpe.br/

## Screenshot
See `screenshot.png` included in the repository.

## Reproducibility & Innovation
The project is reproducible, based on open-source data and a single prompt to the GPT-4o-mini model. The assistant does not just search, but reasons and proposes specific coordinates, simulating how a real archaeologist might work.
