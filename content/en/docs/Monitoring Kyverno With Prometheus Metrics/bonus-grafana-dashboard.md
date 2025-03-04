---
title: "Grafana Dashboard" 
description: A ready-to-use dashboard depicting insights from Kyverno metrics.
weight: 60
---

## Setup

* Download the dashboard's JSON and save it in `kyverno-dashboard.json`

```sh
curl https://raw.githubusercontent.com/kyverno/kyverno/main/dashboard/grafana/dashboard.json -o kyverno-dashboard.json
```

* Open your Grafana portal and go to the option of importing a dashboard.

* Go to the "Upload JSON file" button, select the `kyverno-dashboard.json` which you got in the first step and click on Import.

* Configure the fields according to your preferences and click on Import.

* And your dashboard will be ready in front of you.

<p align="center"><img src="https://raw.githubusercontent.com/kyverno/website/main/content/en/docs/Monitoring%20Kyverno%20With%20Prometheus%20Metrics/assets/dashboard-example-1.png" height="300px"/></p>
<p align="center"><img src="https://raw.githubusercontent.com/kyverno/website/main/content/en/docs/Monitoring%20Kyverno%20With%20Prometheus%20Metrics/assets/dashboard-example-2.png" height="300px" /></p>
