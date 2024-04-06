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
Ares is my passion project, but I always have trouble explaining why. It's an RSS Reader, and it's awesome!\
I used to rewrite most of the app once a year, as an exercise in keeping up with new APIs apple releases. Sometimes it goes well, other times the APIs are so buggy one must put SwiftData to the side and use Realm - can you tell I've been burn?

You can find it [here](https://apps.apple.com/pt/app/ares-3-rss-reader/id6455494975?l=en-GB).

### Rede
The trains in portugal are... special. There's really no way of knowing when they are arriving because the train stations were build in 1890, and the only update they got was in 1976 with the instalation of intercoms so people can cringe when the annoucer tries to tell the passengers their [train will be delayed](https://www.youtube.com/watch?v=EJkoChmVn98).\
My solution was to check the Infraestruturas de Portugal website, and use their open but undocumented API to create an application that has this information up-to-date.\
It was build in a weekend, and I'm not particularly proud of it, but I hope to make it better in the future.

You can find it [here](https://apps.apple.com/pt/app/rede-comboios-de-portugal/id1447635458?l=en-GB)

### aCultural
This was my pet project before I had Ares, it served the same objective to keep my skills up to date. Unfortunatly, the API is so poorly documented and changes so frequently it was a hassle to maintain. It used the APIs provided by the Lisbon Municipality about cultural events and interviews to artists. It was basicly an App version of [Agenda Cultural de Lisboa](https://www.agendalx.pt).

It's no longer available in the App Store, but the code is available [here](https://github.com/joaoc-pires/ios-app-acultural).

### eBLX
I have a soft spot for this project. It was the very first app I release in the AppStore in the far gone year of 2016 (or was it 2017?). I since lost it's source code, but I can guarantee it was not pretty, or maintainable. It was basicly scrapping the HTML of the Lisbon Municipal Libraries to provide a usable interface on mobile. May it rest in peace.

It's no longer available anywhere.

### Portugal Trains
It's a wrapper for the undocumented [Infraestruturas de Portugal](https://www.infraestruturasdeportugal.pt) APIs for train time tables. Not sure I can say much more about this one.

You can find it [here](https://github.com/joaoc-pires/lib-portugal-trains)

### PTStations
In order to get all the features I wanted in Rede, I needed some info that was not obtainable via the Infraestruturas de Portugal API. The data needed like coordinates and services close to the train stations such like fire and police department were available but only on a XLSX file in the [Portuguese Open Data Portal](https://dados.gov.pt/pt/datasets/estacoes-e-apeadeiros/). I made this very rude, very poorly documented app to imports this data set and export it as a JSON file. I was then able to more easily use the data within Rede.

You can find it [here](https://github.com/joaoc-pires/macos-app-ptstations?tab=readme-ov-file).\
You can find the output [here](https://joaopires.com/apis/train-stations/all.json).

### Conceal
Conceal is a World of Warcraft addon that hides UI elements when out of combat. There's not much more to it. It's written in Lua, and Blizzard documentation manages to be even worst than Apple's.

You can find it [here](https://github.com/joaoc-pires/wow-addon-conceal).

### HoN Announcer
Another World of Warcraft addon. This one is even simpler, it plays a HoN voice when certain PvP events happen in game. Simple, and hillarious, in my humble opinion.

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