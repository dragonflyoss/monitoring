# Grafana

Grafana dashboard including manager, scheduler, client and seed client.

## Grafana Develop Guide

### Step 1: Import previous version dashboard to grafana

Import the grafana dashboard reference documentation [export-import](https://grafana.com/docs/grafana/latest/dashboards/export-import/).

Dragonfly grafana dashboard info is:

<!-- markdownlint-disable -->

| Name                  | ID    | Link                                         | Description                                                       |
| :-------------------- | :---- | :------------------------------------------- | :---------------------------------------------------------------- |
| Dragonfly Manager     | 15945 | https://grafana.com/grafana/dashboards/15945 | Grafana dashboard for dragonfly manager.                          |
| Dragonfly Scheduler   | 15944 | https://grafana.com/grafana/dashboards/15944 | Grafana dashboard for dragonfly scheduler.                        |
| Dragonfly Client      | 21053 | https://grafana.com/grafana/dashboards/21053 | Grafana dashboard for dragonfly client and dragonfly seed client. |
| Dragonfly Seed Client | 21054 | https://grafana.com/grafana/dashboards/21054 | Grafana dashboard for dragonfly seed client.                      |

<!-- markdownlint-restore -->

### Step 2: Update grafana dashboard and export share file

You need to update the dashboard, then click the grafana share button to export the `.json` file. Please refer to [export-import](https://grafana.com/docs/grafana/latest/dashboards/export-import/).

### Step 3: Publish grafana dashboard

Release new version of dragonfly grafana dashboard needs to be organized at [d7y](https://grafana.com/orgs/d7y).
