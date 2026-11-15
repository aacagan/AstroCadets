WHAT IT DOES AND HOW IT WORKS
Astro Cadets: Launch Day is a 3D Roblox game that puts kids aged 8-12 inside a real launch complex as a junior astronaut. Gameplay happens physically in the 3D world, not in menus. Players walk, run, carry and interact with objects to prepare a rocket for liftoff:
- Fuel: carry fuel canisters to the rocket while avoiding hazards that make them drop the canister.
- Power: connect colored plugs to matching sockets on a wiring panel. The layout is randomly generated every time, so it can't be memorized.
- Communication: control a satellite dish and keep it aligned with a satellite.
- Weather: read wind data and decide GO or HOLD.
- Seatbelts: ride the gantry elevator to the capsule and fasten the harness buckles in the right order.
- Ignition: turn the key and pull the launch lever.
After the checklist, the player counts down from a safety bunker, watches the liftoff and then flies the rocket through a 3D ascent: steering through rings, avoiding clouds, birds and space debris, and protecting the hull. Stage separation follows, and the mission ends in one of three outcomes:
- Success: the rocket reaches orbit, Earth appears, and the player earns a badge, up to 3 stars and a NASA "Did you know?" fact card. The next training station unlocks.
- Partial success: the rocket reaches orbit with warnings, and the player is encouraged to try for a perfect launch.
- Failure: the launch fails in a dramatic but kid-friendly way (the crew escapes safely by capsule). The game explains exactly what went wrong, such as leaked fuel or a wrong wire, and the player can retry.
BENEFITS
Players learn by doing. They experience why every pre-launch step matters, that order and teamwork-style procedures are important, and that mistakes are part of learning. Failure is safe and explained, so it motivates a retry instead of frustration. Real NASA facts attached to each station connect the game to actual space exploration.
INTENDED IMPACT
We want to make space careers and mission procedures feel exciting and accessible to children, on a platform where they already spend their time. The goal is to spark curiosity about space science and engineering, and to give educators and parents a fun way to introduce how astronauts and mission control work. The game is designed to grow into five stations (Launch, Microgravity, Spacewalk, Daily Routine, Landing) that together cover a full astronaut training journey.
TOOLS AND TECHNOLOGIES
- Roblox Studio and the Luau programming language
- AI-assisted "vibe coding" with an AI coding assistant to generate and iterate on scripts
- All 3D models (rocket, launch pad, gantry tower, elevator, control room, fuel depot, satellite dish, weather station, bunker) are built procedurally from Parts by code, with no external assets
- Roblox services: TweenService, ProximityPrompt, ClickDetector, constraints, Attachments, ParticleEmitter, Lighting effects (Atmosphere, Bloom, ColorCorrection, SunRays)
- Architecture: server-validated tasks, a client for input and camera, ModuleScripts per station, and a CONFIG table for tuning difficulty
- GitHub for the public project repository, and NASA educational resources for the fact cards
CREATIVITY
Instead of a quiz or a click-through simulator, we built a living launch site where every task is a physical activity: carrying fuel, wiring a panel, steering a dish, riding an elevator, flying the rocket. Cinematic cutscenes, particle-based engine exhaust, hold-down clamps releasing before liftoff, and three different endings make each launch feel unique. Randomized wiring and harness orders make every attempt different, and the failure ending turns mistakes into a learning moment instead of a punishment.
FACTORS WE CONSIDERED
- Audience: kid-friendly visuals, language and failure scenes (no scary content), with clear objectives, key hints on objects and a guiding beam so no one gets lost.
- Platform: Roblox is where kids already play, supporting keyboard and touch controls.
- Education: tasks mirror real launch preparation steps and NASA facts are shown right after play.
- Replayability: random task layouts, scoring based on errors, timing and flight performance, and three endings.
- Time constraints: a modular design lets us add new stations without changing existing ones, and debug tools let us test every phase quickly.
- Accessibility of the submission: the project link is a public GitHub repository with screenshots, scripts, the demo video and the Roblox game link, so reviewers do not need an account to see the project.
