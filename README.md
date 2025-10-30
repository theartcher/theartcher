# Joris Brugman

Hello and welcome to my GitHub profile! Here I keep all my cherished projects, both personal as well as group projects. I am Joris Brugman, I am currently 21 years of age and, as you guessed it, I love programming. For me I really like the soft-skills part of it, translating wishes of a user or a PO into a proper, maintainable product is very rewarding to me.

- [Joris Brugman](#joris-brugman)
  - [Fontys ICT projects](#fontys-ict-projects)
    - [S1 - Trash4Cash](#s1---trash4cash)
    - [S3 - SpottedCharts](#s3---spottedcharts)
    - [S4 - Smart Mobile](#s4---smart-mobile)
    - [S5 - Internship](#s5---internship)
    - [S6 - Advanced Software](#s6---advanced-software)
    - [S7 - DesignPatternPedia](#s7---designpatternpedia)
  - [Hobby projects](#hobby-projects)
    - [Freazy](#freazy)
    - [ConnectMi](#connectmi)
    - [FriendsINC.js](#friendsincjs)
    - [Helldivers 2 theme on the N3DS](#helldivers-2-theme-on-the-n3ds)
  - [Get in touch](#get-in-touch)

## Fontys ICT projects

Each of my Fontys projects has been separated into a (public) organization as to keep my profile clean. You can find working links to each repository in their respective section. If a semester is not visible, that is likely to a signed NDA or a lack of a public Git (-> Fontys local Gitlab).

### S1 - Trash4Cash

Ah my first project ever at Fontys ICT. We worked on a sustainability, we tried to achieve this by focussing on [SDGs](https://sdgs.un.org/goals), which are essentially 17 goals for the most optimal, sustainable future of humankind.

\> [Repository](https://github.com/theartcher/Trash4Cash)

_Technologies used;_

- React Native (JavaScript) frontend
- Express & Sequelize (JavaScript) backend
- MySQL database

### S3 - SpottedCharts

Semester 3 was my first real experience with Docker, writing actual documentation and CI/CD via GitHub Actions. The application involved reading some user data from Spotify, authenticated through an OAuth system. The user could request their latest artists, songs, and genres. These were then stored and this allowed the user to plot changes over time using our app.

\> [Repository](https://github.com/S3-Software-IP/monorepo)

_Technologies used;_

- Next.Js frontend
  - Jest for tests
- ASP.NET Core Web API backend
- MySQL database

### S4 - Smart Mobile

Smart mobile was divided into 2 very separate tracks, a duo project and a group project. The duo project focused on creating 2 apps, both in Flutter. Both focussed primarily on the UX/UI part, since my group mate and I had already 'mastered' the technical side of things. More details regarding these two projects you can find in their respective repositories.

- [Duo cases repository README](https://github.com/S4-Smart-mobile/S4-Smart-Mobile?tab=readme-ov-file)
- ['Cultural Exchange' case](https://github.com/S4-Smart-mobile/S4-Smart-Mobile/tree/main/Cultural%20Exchange%20App)
- ['Mood predictor' case](https://github.com/S4-Smart-mobile/S4-Smart-Mobile/tree/main/mood_predictor_app)

For the group project, [we won a 1500 euro price for 'Best Concept Smart Mobile'](https://www.linkedin.com/posts/joris-brugman-1186131b9_dear-network-i-am-extremely-proud-to-announce-activity-7231270908823310336-LWme?utm_source=share&utm_medium=member_desktop&rcm=ACoAADLQfeQB00PkaEW2bi0fsZjwH-H8SqR0iFE) regarding the topic 'Sensory Overload', also known as overstimulation. During this project I worked with talented designers and software engineers alike to create a mobile VR experience. We recorded our own 360 degree camera footage, which we then implemented into our own hand-made cardboard VR headsets. The app helped individuals suffering from sensory overload to give a look into their life to their loved ones. A user can select an experience, the 'overloadness' they want to experience and then just jump right in. With various sounds and sights we try to actively overstimulate a person' perception. We showcased this to one of our stakeholders, an older man who, due to major brain trauma suffers from regular, excessive overstimulation. With our product we were able to help him explain to his grandchildren better why he sometimes could not interact with them, without being sounding harsh or distant.

\> [LinkedIn post discussing the project](https://www.linkedin.com/posts/joris-brugman-1186131b9_dear-network-i-am-extremely-proud-to-announce-activity-7231270908823310336-LWme?utm_source=share&utm_medium=member_desktop&rcm=ACoAADLQfeQB00PkaEW2bi0fsZjwH-H8SqR0iFE) </br>
\> [Repository](https://github.com/StudioKrom-SmartMobile-2024/frontend) </br>
\> [Interview with Studio Krom](https://www.linkedin.com/feed/update/urn:li:activity:7231578870137704448/)

_Technologies used;_

- Flutter
- MQTT

### S5 - Internship

During my internship I did exploratory research into large-scale data orchestration and transformation tooling for [ISPnext](https://www.ispnext.com/en/). As they can better explain themselves:

> ISPnext increases the financial impact of more than 450 organizations with AI-driven solutions for Business Spend Management (BSM). A single platform for cost savings, contract management, strong supplier relationships, automated invoice processing and reduced risks. The result: informed decisions, room for growth and higher profitability.

For this they needed an updated methodology to be able to handle large scale SQL-based traffic on their various complex database systems. I looked into Dagster, Apache Airflow, Prefect and DBT. Creating a large, comprehensive guide on their technical capacities with demos to prove it's business worth and stake my case.

\> [LinkedIn post](https://www.linkedin.com/posts/joris-brugman-1186131b9_dear-network-id-like-to-take-a-moment-activity-7288888721712513024-Xoh3?utm_source=share&utm_medium=member_desktop&rcm=ACoAADLQfeQB00PkaEW2bi0fsZjwH-H8SqR0iFE)

_Technologies used;_

- Dagster
- Prefect
- Apache Airflow
- DBT
- SQL
- Python

### S6 - Advanced Software

In my 6th semester I focussed on creating a complex, distributed software architectural system. I created 'Cockatoo', a Twitter/X clone. This offered me the opportunity to go into more technical topics such as creating a distributed system using various tooling. I started off with Docker, moved to Minikube, which then continued onward to Azure Kubernetes Services. In Azure I worked in registering my own application properly. This included creating a message bus, working with Azure Functions and getting all of that working in a full CI/CD using Github Actions. Code quality was validated using K6 for load tests, SonarCloud for static code analysis and Git Guardian for any outstanding Git related security issues. The distributed system is seperated into 5 repositories.

- [Semester organization](https://github.com/orgs/S6-AdvancedSoftware-Individual/repositories)
- [Posts service](https://github.com/S6-AdvancedSoftware-Individual/post-service)
- [Frontend](https://github.com/S6-AdvancedSoftware-Individual/cockatoo-frontend)
- [Accounts service](https://github.com/S6-AdvancedSoftware-Individual/accounts-service)
- [Gateway](https://github.com/S6-AdvancedSoftware-Individual/cockatoo-gateway)
- [Infrastructure & load test](https://github.com/S6-AdvancedSoftware-Individual/cockatoo-infrastructure)

_Technologies used;_

- Azure (Functions, Kubernetes Service & Postgres Database hosting)
- Kubernetes
- Docker
- ASP.NET Core Web APIs
- K6
- Vue.js
- Ocelot gateways

For the group project, I worked on an algorithm which allows a user to charge their electric vehicles in a smart, sustainable manner. The project allowed for electricity trading, complex charging schedules for both commercial as well as personal vehicular management. In order to make this all work we had to integrate various external APis such as SolarEdge, Frank Energie, TOMP, WallBox and so forth. The complex nature of data ingesting and poorly documented web APIs proved a difficult challenge to tackle.

Sadly there is no repository available for this project due to contractual obligations.

_Technologies used;_

- Python
- GraphQL

### S7 - DesignPatternPedia

In my current semester, my 7th, I have been working on learning more, in depth about various design patterns. This semester has mixed goals, it offers me an opportunity to learn more about technical side of these patterns. As well as allowing me to create a well-documented open-source project with no business incentive. I am a strong believer of making knowledge as free and accessible as possible. This site has just that, it is fully open-source, accessible, available and open about it's intentions. It is created to help others learn the design patterns in a structured and approachable manner. It has a requirement to not have any commercial benefits. This includes cookies, advertisements, tracking of any sorts, any sort of paid hosting or paywalls for that manner.

- [Production environment](https://s7-openlearning-individual.github.io/DesignPatternPedia/)
- [GitHub Organization](https://github.com/orgs/S7-OpenLearning-Individual/repositories)
- [Wiki Repository](https://github.com/S7-OpenLearning-Individual/DesignPatternPedia)

_Technologies used;_

- Docusaurus (framework)
- React

## Hobby projects

In this section I will go over some of my person projects. This'll include some background context, my inspiration for getting started, goals and perhaps even a reason why it's on the back burner.

### Freazy

Freazy was originally a small "I'm gonna make this real fast" project. But it grew out to something larger quite fast. My mother-in-law has 3 freezers (don't ask me why), and she needed help managing them. However the app she was using for this had quite a few problems associated with it, to name a few;

- Outdated Android, could not be installed on her newer, modern phone.
- Really poor UI
- Horrible customization experience, hard to change languages, preferred time formats etc.

I had just finished my semester of [Smart Mobile](#s4---smart-mobile) and full of confidence I started working on creating Freazy. The new and improved app worked with a modern framework called [Flutter](https://flutter.dev/). Some of the noteworthy mentions in the V1 release;

- An overview of all the products a user has registered.
- Export- and importing backups.
- Autofill when adding new products based on products already in the database.
- Real-time validation to guide the user.
- Full localization (l10n) support for both Dutch as well as English including timestamps, decimal separators and the actual text.
- Full dark, light, and system theming support.
- Daily background reminders for products expiring based on criteria the user selects (E.g. 1 week before expiring send a notification).

This has been put on the back burner due to some priorities with my work, searching for an internship and Fontys related projects.

- [Repository](https://github.com/theartcher/freazy)
- [Wiki on Notion](https://pastoral-almond-4c5.notion.site/Freazy-225b5f8e336c80749c51e10b660d5af5)

_Technologies used;_

- Flutter

### ConnectMi

The ConnectMi mobile app went through various iterations in it's short life-span. I started on this project to create an alternative to the [esp8266_milight_hub](https://github.com/sidoh/esp8266_milight_hub) web interface, as it [looked quite bad](https://user-images.githubusercontent.com/589893/61682228-a8151700-acc5-11e9-8b86-1e21efa6cdbe.png) prior to it's 1.13.0 release. This project mainly focussed on

- Maintaining state between devices with questionable internet connectivity.
- Designing a mobile app ([v1](https://github.com/theartcher/ConnectMi/blob/main/ConnectMi-v1.pdf) & [v2](https://github.com/theartcher/ConnectMi/blob/main/ConnectMi-v2.pdf)).

This project was put on the back burner for three reasons;

- Milight hub released a completely new, revamped UI not too long after finishing the initial designs.
- I figured out just how unstable the HTTP connection was to the hub.
- I could integrate using HomeAssistant, avoiding the need all together to develop an app.

It was a very fun and interesting experience designing something for a mobile application though.

\> [Repository](https://github.com/theartcher/ConnectMi)

_Technologies used;_

- Figma
- Flutter

### FriendsINC.js

My absolute first project I ever put on GitHub, it was my introduction to JavaScript, git, web APIs and, programming in general. There was absolutely plenty of room for improvement, but it was such a fun project to create at the time. To be able to sit behind my desk, type something and then make it WORK was fantastic and incredibly rewarding. I hosted it on a server via Cubes.host which had a Postgres server included in the plan. Although small I learnt a lot.

\> [Repository](https://github.com/theartcher/Friends.INC/blob/main/FriendsINC.js)

_Technologies used;_

- JavaScript
- Discord Web API

### Helldivers 2 theme on the N3DS

Although not a very technical project, it is a fun one regardless. It is comically well documented for how small the project actually is. I had (hadn't\* in case Nintendo is reading this) hacked my 3DS to play some old, nostalgic games on it again, and I wanted a nice theme on it. I got into Helldivers 2 semi-recently and was instantly hooked, thus I wanted to make my own theme for it.

\> [Repository](https://github.com/theartcher/hd2-3ds-theme)

## Get in touch

Do you look what you've seen on my profile so far, have any questions regarding my repositories or would just like a quick chat. I recommend you to email me [joris@toqira.nl](mailto:joris@toqira.nl), from there I'd be more than happy to share my phone number with you as well. You can also find me on [LinkedIn](https://www.linkedin.com/in/joris-brugman-1186131b9/).
