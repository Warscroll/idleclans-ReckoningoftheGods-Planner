Reckoning of the Gods Raid Planner — Idle Clans

An all-in-one, single-page raid planner designed for Idle Clans, displaying:

    Player fetch & skill checks from the IdleClans API.
    Automatic role assignment (Combat + Support).
    Gemstone usage priority tables.
    Name-click to fill in repeated participants, saved via localStorage.

Features

    Role Assignment: Assigns Archery (only if level ≥ 90), Magic, or Melee based on skill levels and a “big gap” heuristic for Magic vs. Melee.
    Support Roles: Distributes Plundering, Fishing, and Cooking roles among the team.
    Gemstone & Gear Access: Highlights which gem tiers or gear each player can craft/equip.
    Dark Mode: Switchable theme with persistent storage in localStorage.
    Name History: Previously used usernames are saved in localStorage, so you can quickly re-add them.

Usage

    Clone or Download this repository.
    Open index.html (or your chosen filename) in your favorite browser.
    Enter your username and select the number of other players.
    Fetch & Calculate to retrieve player data and see assigned roles.

Requirements

    A modern browser (Chrome, Firefox, Edge, Safari) that supports JavaScript fetch() and ES6 features.
    A stable internet connection to query the IdleClans API.

Customization

    Base URLs for images are set in the JavaScript (BASE_URL), which you can modify to point to your own server if needed.
    Dark Mode color variables and fonts can be easily tweaked in the <style> section.
    Archery ≥ 90 logic and other role assignments can be adjusted in the assignRolesAndDisplay() function.
