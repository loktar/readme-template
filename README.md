# {{App Name}}

{{ paragraph explaining what this repo is all about }}

## Links

| Environment     | Link                     |
|-----------------|--------------------------|
| Production      | {{ link to production }} |
| {{ Other Env }} | {{ link to other env }}  |

### External Links

| Name            | Link                      |
|-----------------|---------------------------|
| Git Repo(s)     | {{ link to related git repo(s) }} |
| Pivotal Tracker | https://www.pivotaltracker.com/n/projects/{{my-project-id}} |
| CI              | {{ link to CI pipeline }} |
| Miro            | {{ link to Miro board }}  |

## Contribution

### Project Structure

{{ explain project structure; highlight any patterns or major design decisions new contributors should know about }}

| `/ci` | CI configuration files and scripts |
| `/{{ other }}` | {{ other part of project structure }} |

### Workstation Setup

{{ Detailed steps to get a fresh machine development ready for this repo }}

### Additional Setup

{{ Any additional setup needed that is not workstation-specific; e.g., creating 3rd party accounts, getting API keys, etc. }}

### Run All Tests

```
{{ command(s) to run all tests }}
```

### Run App(s)

```
{{ command(s) to run all apps }}
```

## Deployment

{{ overview of deployment strategy; where is the app deployed; explain if we deploy from branches or master, from CI, etc. }}

### PCF Configuration

{{ explain any non-trivial services in use; e.g., config server, cups, etc. }}

### {{ Env 1 }}

{{ how to deploy to Env 1 }}

### {{ Env 2 }}

{{ how to deploy to Env 2 }}

## Common Maintenance Tasks

### {{ Task 1 }}

{{ 

To perform Task 1: 

1. {{ subtask 1 }}
1. {{ subtask 2 }}
1. {{ subtask 3 }}

}}
