Architecture Overview

The application consists of multiple services running as containers.

Architecture components:
- Frontend service (user interface)
- Backend service (application logic)
- Container networking for service communication

Services communicate over Docker-managed networks,
allowing isolated and controlled interactions.

Each service runs independently, enabling easier troubleshooting
and service restarts without impacting the entire system.
