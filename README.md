<img src="assets/header.svg" alt="Eva Legrand, software engineer" width="100%"/>

**[Connect on LinkedIn →](https://www.linkedin.com/in/eva-legrand/)**

I am Eva, a 5th-year software engineering student at [Epitech Paris](https://www.epitech.eu/) (class of 2027).

I like systems where many things happen at once: a game server juggling a dozen AI players, a core that swaps graphics libraries while the game runs, a back end talking to fifteen third-party APIs. Most of my projects are some version of that.

&nbsp;

## What I work on

|  |  |
|---|---|
| **Back end** | REST APIs in Go and TypeScript (Express), layered architecture, OAuth2, PostgreSQL |
| **Front end** | React and TypeScript |
| **Architecture** | Microservices, routing and gateway, Docker |
| **Systems and games** | C and C++, ECS engines, UDP and TCP networking, multithreading and processes |
| **Quality** | Unit tests, CI with GitHub Actions, conventional commits |

&nbsp;

## Stack

<p>
<img src="https://skillicons.dev/icons?i=c,cpp,go,ts,haskell&theme=dark" alt="C, C++, Go, TypeScript, Haskell" height="44"/>
&nbsp;&nbsp;
<img src="https://skillicons.dev/icons?i=react,nodejs,express,vite,tailwind,flutter&theme=dark" alt="React, Node.js, Express, Vite, Tailwind, Flutter" height="44"/>
&nbsp;&nbsp;
<img src="https://skillicons.dev/icons?i=postgres,docker,githubactions,cmake,linux,git&theme=dark" alt="PostgreSQL, Docker, GitHub Actions, CMake, Linux, Git" height="44"/>
</p>

&nbsp;

## Building right now

<table>
<tr>
<td width="40%" align="center"><a href="https://playforward.fr"><img src="assets/playforward.gif" alt="PlayForward and its mascot" width="100%"/></a></td>
<td valign="middle">
<h3><a href="https://playforward.fr">PlayForward</a></h3>
<sub>TypeScript · Express · React · microservices</sub><br/><br/>
An indie game discovery platform that ranks games by what you play, how long you play them and what you tell it, never by ad budget. <i>Search less, play more.</i><br/><br/>
<b>Right now:</b> the communities service (type boundaries and routing behind the gateway), and A/B testing the slogan with a survey before locking the wording.
</td>
</tr>
</table>

&nbsp;

## Selected projects

<table>
<tr>
<td width="40%" align="center"><a href="https://github.com/Chaegnal/area"><img src="assets/area.png" alt="AREA" width="100%"/></a></td>
<td valign="middle">
<h3><a href="https://github.com/Chaegnal/area">AREA</a></h3>
<sub>Go · React · Flutter · PostgreSQL · Docker</sub><br/><br/>
Workflow automation in the style of Zapier. Connect GitHub, Spotify, Discord or Reddit and chain &quot;when this happens, do that&quot;. A web client and a mobile app share one API.<br/><br/>
<b>My part:</b> the Go back end (684 of ~2,000 commits): layered architecture, OAuth2 services and the unit tests.
</td>
</tr>
<tr>
<td width="40%" align="center"><a href="https://github.com/Chaegnal/r-type"><img src="assets/r-type.gif" alt="R-Type" width="100%"/></a></td>
<td valign="middle">
<h3><a href="https://github.com/Chaegnal/r-type">R-Type</a></h3>
<sub>C++ · ECS · Asio · raylib · CMake</sub><br/><br/>
A multiplayer shoot'em up on a home-made ECS engine and a UDP server: four players against waves and bosses.<br/><br/>
<b>My part:</b> game logic, level switching, the level 2 and 3 bosses, firing systems and server threading (123 of 745 commits).
</td>
</tr>
<tr>
<td width="40%" align="center"><a href="https://github.com/Chaegnal/Zappy"><img src="assets/zappy.gif" alt="Zappy" width="100%"/></a></td>
<td valign="middle">
<h3><a href="https://github.com/Chaegnal/Zappy">Zappy</a></h3>
<sub>C · C++ · raylib · TCP</sub><br/><br/>
AI teams survive and evolve on a shared map. A C server, C++ AI clients and a 3D viewer where the players fly over the islands.<br/><br/>
<b>My part:</b> server commands (look, broadcast, the graphical protocol), the win condition and tests (112 of 527 commits).
</td>
</tr>
<tr>
<td width="40%" align="center"><a href="https://github.com/Chaegnal/Arcade"><img src="assets/arcade.gif" alt="Arcade" width="100%"/></a></td>
<td valign="middle">
<h3><a href="https://github.com/Chaegnal/Arcade">Arcade</a></h3>
<sub>C++ · SFML · SDL2 · ncurses</sub><br/><br/>
A retro gaming platform where games and graphics libraries are plugins loaded at runtime, so any game runs on any renderer.<br/><br/>
<b>My part:</b> the three graphics libraries, Pacman, Nibbler and the menu (35 of 72 commits, shared with one teammate).
</td>
</tr>
<tr>
<td width="40%" align="center"><a href="https://github.com/Chaegnal/RPG"><img src="assets/dragon-burden.gif" alt="Dragon Burden" width="100%"/></a></td>
<td valign="middle">
<h3><a href="https://github.com/Chaegnal/RPG">Dragon Burden</a></h3>
<sub>C · CSFML</sub><br/><br/>
A top-down RPG written in C during my first year, with a village, a quest line and an inventory. Team of four.<br/><br/>
<b>My part:</b> menus, maps, quests and inventory (18 commits).
</td>
</tr>
<tr>
<td width="40%" align="center"><a href="https://github.com/Chaegnal/My-Teams"><img src="assets/my-teams.png" alt="My Teams" width="100%"/></a></td>
<td valign="middle">
<h3><a href="https://github.com/Chaegnal/My-Teams">My Teams</a></h3>
<sub>C · TCP · POSIX</sub><br/><br/>
A Teams-style chat. One server handles many clients at once: teams, channels, threads and private messages, saved to disk.<br/><br/>
<b>My part:</b> the server command layer, user and team commands, and persistence (26 of 81 commits).
</td>
</tr>
</table>

**Also:** [Raytracer](https://github.com/Chaegnal/Raytracer) (C++20 ray tracer with a scene parser) · [The Plazza](https://github.com/Chaegnal/The-Plazza) (pizzeria simulation with processes, IPC and thread pools) · [Image Compressor](https://github.com/Chaegnal/Image-Compressor) (k-means in Haskell)

&nbsp;

## Open source

I wrote the **`organizer`** realm for [gnolang/gno](https://github.com/gnolang/gno), a smart-contract platform written in Gno (an interpreted Go). It lets friends plan outings, with groups, hangouts, tests and documentation. About 100 commits between April and July 2025, including security fixes and filetests. [My fork](https://github.com/Chaegnal/gno).

&nbsp;

## Let's talk

If you want to talk back ends, game engines, or why a game recommendation should never be a paid placement, **[LinkedIn](https://www.linkedin.com/in/eva-legrand/)** is the fastest way to reach me.
