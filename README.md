# Vervoerregio Amsterdam | Toolgankelijk

![image](static/readme-images/vvr-logo.png)

## Contents

- [Description](#description)
- [Features](#features)
- [Design Choices](#design-choices)
- [Datamodel](#datamodel)
- [Installation](#installation)
- [Projectteam 2026](#projectteam-2026)
- [Sources](#sources)
- [Licence](#licence)

## Description

Vervoerregio Amsterdam connects munancipilities and works on a ragion where people can achieve their destination easily. The municipalities Aalsmeer, Amstelveen, Amsterdam, Diemen, Edam-Volendam, Haarlemmermeer, Landsmeer, Oostzaan, Ouder-Amstel, Purmerend, Uithoorn, Waterland, Wormerland, Beemster, Purmerend en Zaanstad together forms Vervoerregio Amsterdam. Vervoerregio Amsterdam exist out of 14 munancipilities.

Vervoerregio is a client of the public transportation per bus, tram, metro.

Toolgankelijk is an ongoing project at FDND-agency that has been developed by alternating teams since 2023. Within this project, a website with an audit tool has been developed, allowing partners of Vervoer Regio Amsterdam to test their websites for accessibility according to EAA legislation.

With the application you can run a performance audit, to check the status of your website. After you run the test it you will see the results of the automatically tests. There are some audits you have to check manually. There is a second [repositry](https://github.com/fdnd-agency/toolgankelijk-audit). When you need to run a performance audit make sure you run this in the background.

![image](static/readme-images/partners-overview.png)

## Design System

<img width="234" height="482" alt="Screenshot 2026-06-03 at 13 15 52" src="https://github.com/user-attachments/assets/85ba2db4-a7d7-40bf-a840-51b76b77b32d" />

This design system serves as the blueprint for the visual direction of the application within this project. It defines design decisions, style elements, and reusable components, creating a clear and consistent foundation for the further development of the product. In this way, the team can work from the same design principles, making it easier to add new features without compromising the overall consistency and coherence of the application.

<a href="[url](https://www.figma.com/design/u9GyhD6jIajigsWlHYBuWj/Design-System---Vervoerregio-Amsterdam?node-id=1-830&t=IC3XiL7krvLuWoKn-1)">Design System figma file</a>

## New Design

This is the most up to date design of the application with the design system implemented in Figma. It reflects the current visual direction and the agreed design choices for the project. However, the design still needs to be implemented into the official application, meaning the next step is to translate these Figma components and styles into the working product so that the interface fully aligns with the defined design system.
Homepage

<img width="1440" height="1047" alt="Homepage" src="https://github.com/user-attachments/assets/8efc8e33-15d5-4500-892a-59f1c973a3ed" />

By applying a layout grid and a fixed color palette to the homepage, it already looks much more structured than before. The new design has not yet been fully implemented on the home page, but it is clearly moving in the right direction.

Partner Cards

<img width="624" height="196" alt="Partner Cards" src="https://github.com/user-attachments/assets/185b5829-c3b2-450a-93b9-8df78267d73f" />

By only adjusting the color palette, the card already feels and looks much less cluttered and more balanced. The reduced contrast and more consistent use of colors help improve readability and create a calmer visual structure, making the content easier to scan and understand.

URL screen

<img width="1440" height="1047" alt="URL screen" src="https://github.com/user-attachments/assets/16f7d012-1aa3-4b18-bb81-6fd1dc48149a" />

I have changed the flow of the website by combining the URL screen with the WCAG (Web Content Accessibility Guidelines). This improves the overall understandability of the application and creates a more logical and streamlined user experience. By bringing these elements together, users no longer need to switch between separate sections, which reduces friction and makes the navigation more intuitive. As a result, the information is easier to access and the structure of the application feels more coherent and consistent.

Checklist

<img width="1440" height="1047" alt="RMC url checklist3" src="https://github.com/user-attachments/assets/91ae67e0-328d-4c97-93ea-89f20662a452" />

The overall checklist page was already in a strong state before I joined the project. The only necessary improvement was adding the option to switch between simplified language and the official language. By centralising this setting in one place, the checklist feels less cluttered and more focused, which improves the overall clarity and user experience.

## Datamodel 

<a href="docs/ERD.svg">
  <img src="docs/ERD.svg" alt="Public ERD for Toolgankelijk" width="900">
</a>

Full size: [`docs/ERD.svg`](docs/ERD.svg)

Source: [`docs/ERD-public.mmd`](docs/ERD-public.mmd)


## Installation

```
1. Clone de repository
2. Open de repo in een IDE
3. Installeer npm packages d.m.v. npm install
4. Maak een `.env` bestand aan in de root van het project en vul de benodigde variabelen in (zie `example.env` voor de juiste namen en structuur)
5. Run de localhost d.m.v. npm run dev
```

## Projectteam 2026

- [Tom] - CMD student
- [Maksim](https://github.com/MaksimH2O) – Backend Developer
- [Joost](https://github.com/JoostVDL4) - Frontend Developer
- [Miel](https://github.com/miel775) - Frontend Developer

## Sources 💡

- [Svelte](https://svelte.dev/docs/svelte/overview)
- [FDND agency](https://github.com/fdnd-agency/vervoerregio-amsterdam)
- [Email verificatie setup met Nodemailer](https://www.youtube.com/watch?v=qa-Sh0iM-kM)
- [SvelteKit](https://svelte.dev/docs/kit/introduction)
- [Directus](https://directus.io/docs/)
- [Figma](https://www.figma.com/design/AcoAfiRyevwqXLmdBrbxtG/Toolgankelijk?node-id=18-42&t=vePCwpOn8RYkWthI-1)
- [Netlify](https://www.netlify.com/)
- [Atomic Design System](https://atomicdesign.bradfrost.com/chapter-2/)

## License

This project is licensed under the terms of the [MIT license](https://www.notion.so/LICENSE).
