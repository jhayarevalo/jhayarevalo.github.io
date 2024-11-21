---
title: 'Roller Champions'
description: 'Cross-platform 3v3 sports game by Ubisoft'
image:
    url: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQOEtR8Aq52XtRoXDYX0ntVy6aCMzDa6Vw9UQ&s'
    alt: 'Roller Champions Logo'
worksImage1:
    url: 'https://staticctf.ubisoft.com/J3yJr34U2pZ2Ieem48Dwy9uqj5PNUQTn/icSUnutIoNmeZ72lHzb7M/0bd1db5cc24ef5d1f36393b4d39edbd5/RC_KeyArt.jpg'
    alt: 'Roller Champions Key Art'
platform: PC, Xbox, PS4, Switch
engine: Unity
---
<h2>Summary</h2>
<p class="quote">
    "Roller Champions is a <b>3v3 sports game</b> where you go head-to-head against the opposing team through speed, wit, crushing tackles, and daring dodges! Be the <b>first team to reach five points</b> by throwing the ball through the hoop!"
</p>

<div class="center extra-spacing">
    <a href="https://www.ubisoft.com/en-us/game/roller-champions">
        <button class="btn">Official Website</button>
    </a>
</div>

<h2>My Contributions</h2>
<p>During my time at Ubisoft, the UI team for Roller Champions was composed of two team leads (programming & art), a UX designer, UI artists and UI programmers. The UI programmers were in charge of implementing the artists' work in engine and hooking up the UI to the correct gameplay systems.</p>
<h3 class="sub-title">Gamemode Selection Menu</h3>
<div class="center">
    <img class="pro-img" width="500" height="281" src="/roller_game-mode-menu.gif"/>
</div>
<ul>
    <li><b>Set up screen</b> and link to launch different gamemodes</li>
    <li>Create <b>gamemode tile widgets</b> in Unity from artists' assets</li>
    <li>Implement <b>logic in C#</b> for scheduled 'Skatepark' mini games, 'Ranked' tile visuals and 'Exotic' (limited time) gamemode</li>
    <li>Extensive gamemode <b>locking logic</b> based on real time availibility and <b>onboarding prerequisites</b></li>
    <li>Set up tile <b>animations</b></li>
</ul>

<h3 class="sub-title">Custom Match Screen</h3>
<div class="center">
    <img class="pro-img" width="500" height="281" src="/roller_custom-match.gif"/>
</div>
<ul>
    <li><b>Set up screen</b> and expose configurable custom match settings</li>
    <li>Settings <b>changes broadcasted</b> to all members of the custom match <b>in real time</b></li>
    <li>Pop up dropdown list to <b>assign bots or players</b> from one's Ubisoft Connect friend's list <b>to each team</b></li>
    <li><b>Match host</b> indicator</li>
</ul>

<h3 class="sub-title">Quick Tutorials</h3>
<div class="center">
    <img class="pro-img" width="500" height="281" src="/roller_quick-tutorials.gif"/>
</div>
<ul>
    <li><b>'Moves List'</b> available in game in start menu or in lobby settings</li>
    <li>Set up display <b>widget for a combo list entry</b></li>
    <li><b>Set up layout</b> to display video and description on the right while an entry is hovered</li>
    <li>Set up <b>data table and data structure</b> for designers to insert combos into the 'Moves List'</li>
    <li>Ability for <b>designers</b> to <b>group entries</b> in subcategories and <b>reorder the subcategories</b></li>
</ul>

<h3 class="sub-title">Wheels Store</h3>
<div class="center">
    <img class="pro-img" width="500" height="281" src="/roller_wheels-store.gif"/>
</div>
<ul>
    <li>Set up data table for different <b>Wheels (in-game currency) bundle entries</b> available for purchase</li>
    <li>Link in game action to external <b>Ubisoft Connect store</b></li>
    <li>Display correct <b>currencies</b> based on user's profile</li>
</ul>

<h3 class="sub-title">Voice Chat UI</h3>
<ul>
    <li>Set up <b>voice chat icons</b> for each player's voice chat state (muted, speaking) in game HUD</li>
    <li>Allow a player to set <b>voice chat rules</b> to others through the start menu in game (mute/unmute)</li>
</ul>

<h3 class="sub-title">Multiplayer Cross-platform UI</h3>
<div class="center">
    <img class="pro-img" width="500" height="281" src="/roller_cross-platform-icons.gif"/>
</div>
<ul>
    <li>Create <b>name display widgets</b> that include platform icon and username</li>
    <li>Implement icon logic (what icon is displayed) with <b>cross-platform rules</b> from Microsoft and Sony</li>
</ul>

<h3 class="sub-title">Player Banners</h3>
<div class="center">
    <img class="pro-img" width="500" height="281" src="/roller_player-banners.gif"/>
</div>
<ul>
    <li>Create <b>banner widget</b> with team color information, player display info and banner cosmetics (background and tagline)</li>
    <li><b>Setup 2D</b> banners <b>in 3D spaces</b> (intro animations)</li>
</ul>

<h3 class="sub-title">End-Match Animation</h3>
<p></p>
<div class="center">
    <img class="pro-img" width="500" height="281" src="/roller_end-match.gif"/>
</div>
<ul>
    <li><b>Different UI animation sequences</b> based on: number of <b>Fans (EXP)</b> gained; <b>Rank progression</b> after a Ranked match (promotion, demotion, placement match status, etc.); <b>lootboxes</b> obtained and more</li>
</ul>