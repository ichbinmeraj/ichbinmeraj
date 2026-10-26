# Meraj Safari

Robotics and industrial IoT engineer. Head of IoT & Robotics at Rapid Solutions International (Dubai).
I build the software that connects, tests and diagnoses industrial robots, and I publish the tooling as open source.

## Open-source work

**ABB Robot Web Services (RWS) family**, independent and not affiliated with ABB

- [abb-rws-client](https://github.com/ichbinmeraj/abb-rws-client): TypeScript client for RWS 1.0 (IRC5, RobotWare 6) and RWS 2.0 (OmniCore, RobotWare 7 and 8) with one API for all three. When a controller refuses a call, the error says what is missing, who can supply it and what to do next. On npm.
- [abb-rws-vscode](https://github.com/ichbinmeraj/abb-rws-vscode): RAPID Live, a VS Code extension that connects to an ABB controller. Edit, push and run RAPID, watch variable values, I/O and the event log, back up and restore, work with several robots in one window. On RobotWare 8, running a program needs Allow Motion Control first. On the VS Code Marketplace.
- [abb-rws-daemon](https://github.com/ichbinmeraj/abb-rws-daemon): a small local service that holds one session per controller, so every program on the PC reads the same state. Read-only. On npm.
- [abb-rws-mcp](https://github.com/ichbinmeraj/abb-rws-mcp): an MCP server on the daemon, so an AI assistant can ask a robot what it is doing and why it stopped. It only reads. There is no write tool. On npm and in the MCP Registry.
- [abb-rws-ros2](https://github.com/ichbinmeraj/abb-rws-ros2): controller state as ROS 2 topics, on the daemon. Early development, built from source (ROS 2 Jazzy).

All of it has been tested on RobotStudio virtual controllers (RobotWare 6.16, 7.21 and 8.2), not yet on a real one. If you run any of these against a real controller, open an issue with the RobotWare version and what the controller answered.

**Fairino cobots**

- [fairino-fws](https://github.com/ichbinmeraj/fairino-fws): REST + WebSocket gateway for Fairino FR-series controllers. Live telemetry, bounded motion, program management, fault dumps, telemetry recordings, Prometheus metrics, a hardware-free simulator. Published on PyPI.
- [fairino-fws-console](https://github.com/ichbinmeraj/fairino-fws-console): operator console for FWS with a 3D arm view, jogging, programs, I/O, force readout and fault decoding.

## Elsewhere

- Website: merajsafari.info
- LinkedIn: linkedin.com/in/merajsafari
- npm: merajsafari
- VS Code Marketplace: MerajSafari
- Email: merajsafari@yahoo.com
