# Capitana: First Lunar Base

An educational lunar mission trainer. A playable five-turn prototype for the Junior Astronaut Mission Trainer challenge. It is an educational game, not a validated engineering simulator or a submitted competition entry.

## Play and presentation

Game: https://alfi-b2bytes.github.io/capitana-lunar-trainer/

Seven-slide English demo (anyone with this link can view): https://drive.google.com/file/d/1qHqZ09H7_c9cGssNonCAgrFetmE51EqB/view?usp=drivesdk&authuser=alfi%40b2bytes.dev

PDF font notices: https://drive.google.com/file/d/1eATkbTbYAYq1TV_sSCdngQEubR2bhsTg/view?usp=drivesdk&authuser=alfi%40b2bytes.dev

Team: B2Bytes. Members as listed on the registered team page: Diego Díaz and Lya Mundaca Acuña. No NASA endorsement.

## Run

Open `index.html` in a modern browser. It is a self-contained, static application with no build step, server, API key, account, payment, telemetry, or personal-data collection. The embedded JSON preserves the source record and qualifications for inspection.

## Playable prototype

- Mission introduction and a no-punishment training promise.
- Abstract avatar selection without real names or photos.
- Five-system science explorer: energy, air, food and water, radiation, and communication.
- Optional comfortable pause with no medical promise or scoring effect.
- Source drawer with a real, dated NASA CCMC DONKI solar energetic particle record.

Version 2 adds three shuffled choices per system, role-specific crew radio channels, visual system progression, an interactive DONKI evidence-reading checkpoint before the radiation plan, and a no-name SVG postcard saved only when the player requests it. There is no automatic sharing or tracking.

The mission includes four crew roles with three qualitative working-style profiles each, a main-thruster fault with intact life support and return module, a repair/support introduction, five system decisions with checkpoints, and a final learning check. No hidden numerical bonuses. A repair never ends the game.

The team approved the four implementation rules on 15 November 2026: main-thruster fault with intact support/return module; five turns; a working base plus learning explanation to win; qualitative crew strengths without invented percentages.

## NASA source data

Historical event: `2024-05-10T13:35:00-SEP-001`, recorded at `2024-05-10T13:35Z`, GOES-P: SEISS >10 MeV, M2M_CATALOG version 1.

Original record: https://kauai.ccmc.gsfc.nasa.gov/DONKI/view/SEP/30677/1

This record informs a historical training scenario. It is not live telemetry, lunar dosimetry, an astronaut exposure estimate, or a forecast. All fictional resource changes and decision outcomes must be labeled educational simplifications. No unread BVAD values are used.

Additional NASA references, verified 15 November 2026:

- Energy and illumination: https://moon.nasa.gov/resources/162/on-the-rim/
- Carbon dioxide removal: https://www.nasa.gov/ochmo-tb-004-carbon-dioxide-2/
- ISS plant research, not lunar-farm data: https://www.nasa.gov/exploration-research-and-technology/growing-plants-in-space/
- Radiation monitoring: https://www.nasa.gov/directorates/esdmd/hhp/space-radiation/
- Planned lunar networking: https://www.nasa.gov/communicating-with-missions/lunanet/

## AI assistance and attribution

Concept and direction: Diego and Lya. AI assisted implementation, interface code, the illustrative code-generated scene, explanatory text, source verification, and testing. AI also proposed specific rule options and later gameplay improvements. Diego approved the initial rule proposals; approval does not change their AI origin. The original DONKI event is NASA source data, not AI-generated data. Generated illustration is visibly labeled in the interface. AI assistance is also declared in HTML metadata. This statement does not certify human authorship of material of uncertain origin or claim that adoption makes an AI-origin idea human-origin.

No recognizable minors, NASA logos, NASA endorsement, commercial calls to action, medical effects, death scenes, or unverified numerical consumption rates are included.

## License

Original application code is licensed under Apache License 2.0. Source references retain their own terms. No rights or NASA endorsement are claimed over cited source material.


## Tools and resource provenance

Runtime: original self-contained HTML, CSS and JavaScript. No third-party runtime libraries, downloaded photos or audio are included. Illustrative SVG and interface text are AI-assisted original project contributions. NASA references appear above and in the application.

Development and presentation tools used: Python; Playwright for functional browser tests (https://playwright.dev/python/docs/library); python-pptx for the editable slide deck (https://python-pptx.readthedocs.io/en/latest/); LibreOffice for PDF export (https://www.libreoffice.org/); GitHub for source and Pages hosting (https://github.com/alfi-b2bytes/capitana-lunar-trainer). The PDF contains embedded font subsets; their license notices are linked above. The editable PPTX embeds no font binaries. AI-assisted work is declared above, in the game, in its metadata and in the presentation.

## Status and limits

This is not a submitted entry or a certificate of eligibility. The team must review the official submission guide, participant terms, originality statement and the rule that SI must not originate the solution idea. AI did propose specific rules and improvements here; disclosure does not erase that origin. No student learning outcomes have been measured. Test results describe software behavior, not educational effectiveness.


## Bilingual and interactive update, 15 November 2026

English remains the default contest route; Spanish is available through the visible language selector (`es.html`). Changing language restarts the mission. Both include a visibly labeled AI-generated fictional adult Capitana Planeta guide and twelve named fictional crew candidates. No real person or minor is represented. The guide, names, translations and interface treatment were proposed/produced with AI under Diego's requested direction, not claimed as independently human-originated.

The solar workshop lets players drag panels, or select a panel and place it with touch/keyboard controls, between an illuminated ridge and shadow. The base lights up when both panels are placed in the illuminated zone. This is an explicit fictional completion rule, not a NASA power/consumption calculation, real illumination model, or a claim that two panels can power a real lunar base. NASA's On the Rim reference supports the distinction between illuminated terrain, shadow and the need to plan for changing illumination: https://moon.nasa.gov/resources/162/on-the-rim/ . Reserve/storage remains part of the subsequent energy planning decision.

Provenance: the assistant proposed moving panels as an interaction example; Diego selected and approved it at 20:39 on 15 November 2026. AI implemented the workshop and its qualitative two-panel completion condition. Human adoption does not change the AI origin or settle the contest's ideation restriction. No eligibility certification is made.
