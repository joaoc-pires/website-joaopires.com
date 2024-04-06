---
layout: single
title: Projects
author_profile: true
---
**Index**\
[Personal Projects](#personal-projects)
- [Ares](#ares)
- [Rede](#rede)
- [aCultural](#acultural)
- [eBLX](#eblx)
- [Portugal Trains](#portugal-trains)
- [PTStations](#ptstations)
- [Conceal](#conceal)
- [HoN Announcer](#hon-announcer)

[Current Professional Projects](#current-professional-projects)
- [Cortado](#cortado)
- [Ezeep Blue](#ezeep-blue)
- [ThinPrint Mac](#thinprint-mac)
- [Teamplace](#teamplace)

[Old Professional Projects](#old-professional-projects)
- [DECOVinhos](#decovinhos)
- [VisitAR](#visitar)
- [H2O Quality](#h2o-quality)
- [Best Mobile](#best-mobile)
- [myCNAIM](#mycnaim)

## Personal Projects
These are my personal projects—each born from a different motivation. Some were crafted with love, others driven by obsession, and a few simply born out of boredom. Among them, you'll find varying levels of quality—some shining brightly, others just okay. I've left out the downright bad ones, sparing you from those missteps. But each project, regardless of its origin or outcome, holds a piece of my creative spirit.

### Ares
Ares holds a special place in my heart as my passion project, and explaining why isn't always easy, but here it goes: it's an RSS Reader, and it's awesome! For me, the thrill lies in the constant evolution of the app. I used to embark on annual rewrites, not just for the sake of change, but as an exercise in staying abreast of the latest APIs released by Apple. Sometimes, everything goes smoothly, and I can seamlessly integrate the new APIs. However, there are those instances when the APIs turn out to be so buggy that I'm left with no choice but to set aside SwiftData and rely on Realm instead. You could say I've been burned a few times by unpredictable API behavior, but the challenge only adds to the satisfaction when things do work out smoothly.

You can find it [here](https://apps.apple.com/pt/app/ares-3-rss-reader/id6455494975?l=en-GB).

### Rede
The train system in Portugal has its own unique charm, to say the least. With stations dating back to the late 19th century and minimal updates since the 1970s, it's no wonder predicting train arrivals can feel like a guessing game. The only modern touch seems to be the addition of intercoms in 1976, which, let's face it, can sometimes lead to comical announcements about delays that passengers have learned to endure.

In response to this challenge, I took matters into my own hands. I decided to tap into the Infraestruturas de Portugal website and leverage their open, albeit undocumented, API to create an application that provides up-to-date train information. With a weekend's worth of work, I whipped up a solution—not my proudest achievement, but a step in the right direction. My hope is to refine and improve this application in the future, making the train experience just a tad less unpredictable for fellow passengers.

You can find it [here](https://apps.apple.com/pt/app/rede-comboios-de-portugal/id1447635458?l=en-GB)

### aCultural
Before Ares came along, this was my pet project—a labor of love aimed at keeping my skills sharp. Its purpose was akin to Ares: to ensure I stayed up to date with the latest in development. However, unlike Ares, this project faced its own set of challenges. It relied on the APIs provided by the Lisbon Municipality, offering information about cultural events and artist interviews—a sort of app version of [Agenda Cultural de Lisboa](https://www.agendalx.pt).

Unfortunately, maintaining this project proved to be quite the hassle. The APIs were poorly documented, and they seemed to change frequently, throwing a wrench into my efforts to keep the app running smoothly. Despite its setbacks, this project served as a valuable learning experience, teaching me the importance of adaptability and resilience in the face of ever-changing technology landscapes.

It's no longer available in the App Store, but the code is available [here](https://github.com/joaoc-pires/ios-app-acultural).

### eBLX
Ah, the nostalgia of the early days! This project holds a special place in my heart—it was the very first app I released on the App Store, way back in the distant past of 2016 (or was it 2017?). While I've since lost its source code, one thing remains certain: it was far from pretty or maintainable.

Essentially, this project involved scraping the HTML of the Lisbon Municipal Libraries to cobble together a usable interface for mobile users. It may not have been the most elegant solution, but it served its purpose at the time. Rest in peace, dear project—you were a humble beginning to what has become a journey filled with learning and growth.

It's no longer available anywhere.

### Portugal Trains
Sometimes, simplicity speaks volumes. This project serves as a straightforward wrapper for the undocumented APIs provided by [Infraestruturas de Portugal](https://www.infraestruturasdeportugal.pt) for train timetables. There's not much more to say about it—it's a tool designed to streamline access to train schedule information, plain and simple.

You can find it [here](https://github.com/joaoc-pires/lib-portugal-trains)

### PTStations
In order to enrich the features of Rede, I found myself in need of additional information that wasn't accessible through the Infraestruturas de Portugal API. Fortunately, the data I required, such as coordinates and nearby services like fire and police departments, was available—but only in an XLSX file on the [Portuguese Open Data Portal](https://dados.gov.pt/pt/datasets/estacoes-e-apeadeiros/).

To bridge this gap, I hastily put together a rudimentary, poorly documented app. Its sole purpose was to import this dataset and export it as a JSON file. This crude tool allowed me to effectively incorporate the necessary data into Rede, enhancing its functionality and providing users with a more comprehensive experience.

You can find it [here](https://github.com/joaoc-pires/macos-app-ptstations?tab=readme-ov-file).\
You can find the output [here](https://joaopires.com/apis/train-stations/all.json).

### Conceal
Conceal is a straightforward World of Warcraft addon designed to streamline the gaming experience by hiding UI elements when the player is out of combat. Its functionality is simple yet invaluable for many players seeking a cleaner interface during moments of non-engagement.

Developed in Lua, Conceal navigates the intricacies of the World of Warcraft environment, offering a seamless transition between combat and non-combat scenarios. However, creating and maintaining this addon comes with its own set of challenges, particularly due to the lackluster documentation provided by Blizzard—a frustration shared by many developers in the gaming community. Despite these obstacles, Conceal remains a valuable tool for enhancing the gaming experience for World of Warcraft enthusiasts.

You can find it [here](https://github.com/joaoc-pires/wow-addon-conceal).

### HoN Announcer
This particular gem is delightfully straightforward: it plays a Heroes of Newerth (HoN) voice line when specific PvP events occur in the game. Simple yet utterly hilarious, this addon adds a touch of humor to the intense PvP action in World of Warcraft.

With its charming simplicity, this addon embodies the essence of fun and lightheartedness within the gaming community. After all, who can resist a well-timed HoN voice line in the midst of battle? It's a testament to the creativity and humor of addon developers, making the gaming experience all the more enjoyable for players around the world.

You can find it [here](https://github.com/joaoc-pires/wow-addon-hon-announcer-remade).

## Current Professional Projects
These are the professional projects I'm currently involved in. Some projects stem from a genuine passion the whole team had for the subject matter, while others are driven by the pursuit of innovation and efficiency. A few are responses to specific challenges or opportunities within the industry, while others are born out of necessity, addressing critical needs within our organization. Despite their diverse origins, each project reflects a commitment to professionalism and a determination to make meaningful contributions and help our clients.

### Cortado
This app, a flagship product of [Cortado Mobile Solutions](https://www.cortado.com/en/), started out as a mix of SwiftUI and UIKit. While it got the job done, managing it with the Coordinator Pattern was getting clunky. But thanks to the new navigation APIs in SwiftUI, we've spent the past few months streamlining the coordinator. Now, it's way easier to read, maintain, and test.

We're pretty stoked about how this app has shaped up, and we're always cooking up new features. Recently, we rolled out a File Provisioning feature that lets managers share specific files with users right through the app. It's just one more way we're making things smoother for everyone.

You can find it [here](https://apps.apple.com/pt/app/cortado/id1501360018?l=en-GB).

### Ezeep Blue
Cortado Mobile Solutions operates under the umbrella of [Cortado-Holding](https://www.cortado-holding.com/en/), where I'm involved in various crucial projects beyond our flagship app. One standout project is Ezeep, an evolution of our earlier product, ThinPrint, offering cloud printing solutions. Ezeep Blue serves as the mobile extension of this service.

One of the standout features of Ezeep Blue is its seamless ability to scan and print documents on the go. It's a handy tool for users who need to print documents directly from their mobile devices.

You can find it [here](https://apps.apple.com/pt/app/ezeep-blue-printer-app/id1527249451?l=en-GB).

### ThinPrint Mac
I've recently joined the maintenance team for ThinPrint, a legacy product known for its stability and robustness. Written in a mix of Obj-C, C#, and Swift, it's a complex codebase that presents exciting challenges. Despite its complexity, I'm determined to contribute to future iterations and support the team in keeping ThinPrint running smoothly.

You can find it [here](https://download.thinprint.com/clients-tools/thinprint-clients-mac/).

### Teamplace
[Cortado](https://www.teamplace.net/en/teamplace-is-saying-goodbye/) recently announced it's sunset on June 30, 2024.\
I liked Teamplace. It was a fun project that involved cloud storage, permissions, subscriptions, file sharing, file previewing, and much more. It was also a complex code base that mixed Swift and Objective-C.\
Little inside knowledge, our team was creating a proposal to rewrite it from the ground up using the newest technologies and update it's UI.\
I kind of feel sad to see it go.

For now, you can find it [here](https://apps.apple.com/pt/app/teamplace/id318124129?l=en-GB/).

## Old Professional Projects
These are the professional projects I've contributed to in the past, but my involvement has since drawn to a close. While I can't provide insight into their current state, they hold significance as milestones in my professional journey. These projects were undertaken during my tenure at an agency, each representing a unique opportunity for growth and learning.

Most of my freelance work I don't list here because of NDAs.

### DECOVinhos
I had the opportunity to work on this app that offered users the ability to search for wine bottles, predominantly Portuguese but also including some international varieties, and view reviews of these wines by testers from [DECO](https://www.deco.proteste.pt). This app provided multiple search options, allowing users to manually search, scan the wine label, or use the barcode to access the wine review. Additionally, users could check prices and find the closest places to purchase the wines they were interested in. Overall, it was an exciting concept that aimed to enhance the wine-buying experience for consumers by providing valuable information and resources at their fingertips.

### VisitAR
I had the privilege of contributing to a customizable product designed to offer Augmented Reality (AR) experiences to customers, primarily museums. This innovative solution blended Swift, Vuforia, and Unity technologies to create immersive and interactive AR experiences tailored to the unique needs and preferences of each museum. By harnessing the power of AR, this app empowered museums to engage and captivate their visitors in entirely new ways, enriching their understanding and appreciation of the exhibits and collections on display.

### H2O Quality
I had the opportunity to contribute to an app that provided users with access to real-time water quality reports in the Lisbon area. This app served as a valuable tool for residents and visitors alike, offering crucial information about the quality of water in the region. 

### Best Mobile
I was part of the initial development team for the debut version of a new app for Best Bank. One of its standout features was the innovative concept of allowing users to customize their main view with shortcuts, akin to the functionality of Springboard in iOS. Beyond this unique customization option, the app primarily served as a standard banking application, providing users with essential banking services and functionalities.

### myCNAIM
I had the privilege of contributing to this app, designed to provide users with practical information for immigrating to Portugal. This app served as a valuable resource for individuals navigating the complexities of the immigration process, offering essential guidance and information to help them settle into their new lives in Portugal with ease. From visa requirements to residency permits, employment opportunities, housing, and healthcare, myCNAIM aimed to empower immigrants with the knowledge and resources they needed to make informed decisions and successfully integrate into Portuguese society.