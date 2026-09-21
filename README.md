# Hi, I'm Alan 👋

**C++ developer who likes building performance-critical software. Open to co-op roles in backend, systems, and embedded development.**

Most of my work is in modern C++, on software where speed and correctness both matter: emulators, game systems, and backend services. I came to programming after a Bachelor of Science and several years in property development and stone fabrication; the jobs were good but I always felt that it never scratched my itch for problem-solving. I always looked for an outlet after work, whether that was going to chess clubs, jiu-jitsu, or playing different video games. None of them provided the same problem-solving capabilities that programming and software development have allowed me to experience, opening the doors to not only endless interesting problems but also the expression for creativity in one's own ideas and work. 

## Projects

**[CHIP-8 Emulator](https://github.com/alankhal/CHIP-8-Emulator)** · C++, SDL2
A complete interpreter for the CHIP-8 virtual machine. All 35 opcodes run through function-pointer dispatch, the CPU core is fully decoupled from the SDL2 platform layer, and the 60 Hz timers run independently of CPU speed. It passes the standard CHIP-8 test ROM suite, and I wrote Pong in CHIP-8 assembly to test it end to end.

**TradeVault** · C++20, Drogon, OpenAPI, GoogleTest · *in progress*
A team-built trade-capture service with a contract-first REST API. Repository interfaces and dependency injection keep storage swappable, GoogleTest and GoogleMock hold domain logic above 90% line coverage, and GitHub Actions blocks any merge that fails to build, pass tests, or clear clang-tidy.

**Tower Defense** · C++
Enemies re-route with A* the moment the player blocks a path. A spatial grid limits each tower to nearby enemies, cutting targeting checks by roughly 90% and holding 60 FPS with 200+ enemies on screen.

## What's next

Finishing TradeVault, then moving from emulating hardware to programming it directly, starting with microcontrollers and bare-metal C.

## Stack

**Languages:** C++ (11/17/20), C, Python, SQL, JavaScript
**Tools:** CMake, Git, Linux, Docker, GitHub Actions, GoogleTest, Drogon, PostgreSQL

## Contact

alankhalifehzadeh@gmail.com · [LinkedIn](https://linkedin.com/in/alankhalif)
