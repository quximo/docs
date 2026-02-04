---
sidebar_position: 2
---

# Quick Start
```bash
# Initialize a new project
quximo init app-name
```

This command:

* Creates a new service in your Quximo workspace
* Generates the `.quximo/` folder with initial config files
* Sets up default deployment and observability settings

---

### Add Dependencies

```bash
# Add a PostgreSQL database to your service
quximo add pg
```

This command:

* Updates your service configuration in `.quximo/`
* Injects credentials and connection info into your environment
* Updates CI/CD and observability settings for the new dependency

---

### How It Works

All changes made via the CLI are tracked in `.quximo/`:

```
.quximo/
├── service.yaml       # service configuration
└── dependencies.yaml  # added databases, queues, etc.
```
