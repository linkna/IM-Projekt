# Use-Case Specification: Social Gardening

# Table of Contents
- [Analyze Acceleration Behavior](#1-analyze-acceleration-behavior)
    - [Brief Description](#11-brief-description)
    - [Screenshots](#12-screenshots)
- [Flow of Events](#2-flow-of-events)
    - [Basic Flow](#21-basic-flow)
    - [MockUp](#22-mockup)
    - [Feature](#23-feature)    
- [Special Requirements](#3-special-requirements)
- [Preconditions](#4-preconditions)
- [Postconditions](#5-postconditions)

# 1. Analyze Acceleration Behavior

Personen die keinen Garten haben, wollen oft trotzdem, eigenes Gemüse anbauen und nutzen dafür moderne Technologien um Pflanzen in der Wohnung zu ziehen oder versuchen es mit vertikalem Gärtnern auf dem Balkon. Dies bedeutet meist, zu wenig Platz für die gewünschte Vielfalt.
Personen die einen Garten haben, ziehen oft ihre Jungplanzen selbst. Um den gewünschten Bestand zu erreichen, wird bei der Aussaat etwa 30% Verlust kalkuliert. Häufig keimen mehr Pflanzen als erwartet. So entsteht bei Jungpflanzen ein Überschhuss. Die überzähligen Pflanzen werden oft entsorgt.
Bei Gartenbesitzern werden nicht immer alle Beete beplanzt, da sie selbst nicht soviel Bedarf haben, so liegen manche Beet brach, während andere Personen gerne etwas anbauen würden, aber keinen Platz dafür haben.
Social Gardening soll den Nutzern eine Crowd Farming Plattform bieten. Nutzer können mit ihrer Nachbarschaft eine lokale Gartengemeinschaft gründen. Ressourcen können gemeinsam genutzt werden. 
Die Gartengemeinschaft kann als virtuelle Nachbarschaft angelegt werden.
Die virtuelle Nachbarschaft biette einen Marktplatz, um Gesuche zu erstellen. Dem Nutzer werden entsprechend dem Gesuch die passenden Anbieter angezeigt und kann direkt vermittelt werden. Gibt es aktuell kein passendes Angebot, so wird das Gesuch im Marktplatz gepostet.
In der virtuellen Nachbarschaft hat jedes Mitglied ein eigenes Profil. In dem Profil kann der Nutzer sein Angebot und Vermittlungsanfragen verwalten. 

## 1.2 Screenshots


# 2. Flow of Events
## 2.1 Basic Flow

![alt text][ActivityDiagram]

[ActivityDiagram]: https://github.com/linkna... "Activity Diagram"

## 2.2 MockUp

![alt text][Nutzerprofil]

[Nutzerprofil]: https://github.com/linkna/IM-Projekt/blob/master/UseCases/SocialGardening/Social%20Gardening%20Profil.jpg

![alt text][MockUp1]

[MockUp1]: https://github.com/linkna...


## 2.3 Feature

[Feature](https://github.com/linkna/FyF/blob/master/app/src/androidTest/assets/login.feature)

# 3. Special Requirements
## 3.1 Device connection 
The device has to be connected to the internet.
## 3.2 Screen size support 
Since the app can be used on every android phone, there will be many different screen sizes. The layout should not waste space on big screens and should still be readable on small screens.

# 4. Preconditions
## 4.1 App opened on screen
The app must be running and opened on the screen. 

## 4.3 The profile is already created
To login into an account, the profile has to exist.

# 5. Postconditions

## 5.1 Managing success
Map is shown. User can view and edit his profile.

## 5.2 Managing failure

Display a notification, saying that and why (if possible) the login failed.

# 6. Function Points
Value: 13

![alt text][fp]

[fp]: https://github.com/linkna/FyF/blob/master/documentation/UC/login%20fp.JPG
