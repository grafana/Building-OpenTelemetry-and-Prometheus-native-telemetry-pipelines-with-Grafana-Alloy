<img width="1901" height="1042" alt="image" src="https://github.com/user-attachments/assets/b907b8dc-0b0f-4191-ab41-dda20b626e8a" />
<img width="1873" height="1051" alt="image" src="https://github.com/user-attachments/assets/e3dd0e99-f78e-4767-9fda-d3e44daf9e1e" />
<img width="1872" height="1052" alt="image" src="https://github.com/user-attachments/assets/68c41817-7f5b-4247-a23f-bdab60df8dcf" />
<img width="1873" height="1052" alt="image" src="https://github.com/user-attachments/assets/1fb44b38-f114-4381-b741-f33737b37928" />
<img width="1871" height="1051" alt="image" src="https://github.com/user-attachments/assets/3737821c-dd0e-465d-8248-ec41a9f1013c" />
<img width="1872" height="1053" alt="image" src="https://github.com/user-attachments/assets/722500e5-d485-411f-841e-32d729dd0d0b" />

# Resources 
- [Add Grafana Alloy for Beginners YouTube Playlist here]
- [Grafana Alloy documentation](https://grafana.com/docs/alloy/latest/)
  - [Alloy configuration blocks](https://grafana.com/docs/alloy/latest/reference/config-blocks/)
  - [Alloy components](https://grafana.com/docs/alloy/latest/reference/components/)
  - [Collect and forward data with Grafana Alloy](https://grafana.com/docs/alloy/latest/collect/)
  - [Grafana Alloy Tutorials](https://grafana.com/docs/alloy/latest/tutorials/)
- For **solutions to sections and hands on exercises**, check out the branches of this repo
- The learning environment was based off of [grafana/intro-to-mltp](https://github.com/grafana/intro-to-mltp). 
  - This repo is a great resource for learning about the Grafana stack end to end, so check it out if you'd like a full end-to-end working example!
    
# What is Grafana Alloy and when does it make sense to use it? 
<img width="1873" height="1052" alt="image" src="https://github.com/user-attachments/assets/2c5b4c90-e4cb-492f-814d-9a797cd710dd" />
<img width="1872" height="1051" alt="image" src="https://github.com/user-attachments/assets/f0f919f3-b68b-4847-902d-b3b9c1f48a02" />
<img width="1871" height="1050" alt="image" src="https://github.com/user-attachments/assets/57e43ff8-5f3e-4dae-aaa0-5cef3b49645d" />
<img width="1873" height="1055" alt="image" src="https://github.com/user-attachments/assets/ec8c5f44-57cd-45aa-a70b-ba9de37a34fe" />
<img width="1872" height="1052" alt="image" src="https://github.com/user-attachments/assets/b8a046b7-ce48-4837-acd4-ee4149e493c6" />
<img width="1872" height="1051" alt="image" src="https://github.com/user-attachments/assets/fb39f801-a990-4924-b0e6-1f11572ffa29" />

# Grafana Alloy configuration language 101

### Think of Alloy as our trusty pal who can collect, process, and export our telemetry data. 

![Alt Text](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2kweW0xMzU5bzQ3ZHUxZDdnbHFid3I0NGoyd3I2am11eHRoYnRsNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xTiTnuhyBF54B852nK/giphy.gif)

To instruct Alloy on how we want that done, we must write these instructions in a language (`Alloy syntax`) that Alloy understands. 

<img width="1873" height="1052" alt="image" src="https://github.com/user-attachments/assets/87eb530a-eb3b-40d3-90d4-6434609ed067" />
<img width="1872" height="1051" alt="image" src="https://github.com/user-attachments/assets/19e40a8d-7a07-4564-9de2-5dbf2d3570b2" />
<img width="1872" height="1049" alt="image" src="https://github.com/user-attachments/assets/bf15e800-5dbf-4fe8-a467-3446365243c4" />
<img width="1873" height="1053" alt="image" src="https://github.com/user-attachments/assets/44e33cfd-09ff-4363-b972-7a4c4778ec49" />
<img width="1871" height="1050" alt="image" src="https://github.com/user-attachments/assets/33615290-7852-41b9-b12f-6530fab77556" />
<img width="1873" height="1051" alt="image" src="https://github.com/user-attachments/assets/fe66d09c-1f24-4902-ba6d-066679f5c0c4" />
<img width="1871" height="1051" alt="image" src="https://github.com/user-attachments/assets/bd9f447e-58e7-4e67-b2ae-8d8267339745" />
<img width="1872" height="1053" alt="image" src="https://github.com/user-attachments/assets/29fdef87-2f43-49dc-879e-f299ea710c09" />
<img width="1876" height="1054" alt="image" src="https://github.com/user-attachments/assets/344884c6-2fce-427a-b5c5-c633b0ae0a8c" />
<img width="1874" height="1053" alt="image" src="https://github.com/user-attachments/assets/c90366ae-662e-435f-8cfa-0a445839abeb" />
<img width="1874" height="1052" alt="image" src="https://github.com/user-attachments/assets/c72f8819-68c5-46a2-866c-687489e75e2c" />
<img width="1874" height="1052" alt="image" src="https://github.com/user-attachments/assets/dc9519b3-d54d-4fae-bf7b-c7d9c2f63e36" />

The `usage` section gives you an example of how this particular component could be configured. 

<img width="1872" height="1051" alt="image" src="https://github.com/user-attachments/assets/2df884bc-ae97-4d65-975b-95e2904013b9" />

The `arguments` and `blocks` sections list what you could do with the data. Pay close attention to the name, type, description, default, and required columns so Alloy could understand what you want it to do! 

<img width="1873" height="1053" alt="image" src="https://github.com/user-attachments/assets/08888cf8-68cb-48d3-a51b-ed4ca89b1430" />
<img width="1874" height="1052" alt="image" src="https://github.com/user-attachments/assets/2593ceff-7b48-400b-8968-d7c1ee60594d" />
<img width="1875" height="1052" alt="image" src="https://github.com/user-attachments/assets/46edeeee-502c-4002-8a3b-b69b74979de6" />

# Learning environment setup

<img width="1872" height="1050" alt="image" src="https://github.com/user-attachments/assets/2645a894-9e08-43e5-804c-ce01753d1ca7" />

Before getting started, make sure you:
- install [Docker Desktop](https://www.docker.com/products/docker-desktop/) and [Docker Compose](https://docs.docker.com/compose/install/)
  
- clone the repo for the learning environment :
```
git clone https://github.com/grafana/Grafana-Alloy-for-Beginners.git
```
- cd into the project, start a new command-line interface in your Operating System and run: 
```
make run
```
- To stop the environment, use the following command:
```
make stop
```
In a separate terminal, open the project using a text editor of your choice.
- Expand the alloy folder and open the `config.alloy` file.
- We will be using this file to build pipelines for Infrastructure Observability and Applications Observability. 

# Infrastructure Observability
## Collect, process, and export infrastructure logs and metrics
### Section 1: Build a pipeline for infrastructure logs with Grafana Alloy
#### Objectives
- Collect logs from Alloy using the [`logging`](https://grafana.com/docs/alloy/latest/reference/config-blocks/logging/) block
- Use [`loki.relabel`](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.relabel/) to add labels to the logs
- Use [`loki.write`](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.write/) to export logs to Loki

#### Instructions

Open `config.alloy` in your editor and copy the following starter code into it:

```alloy/config.alloy
//Section 1

logging {
  format = "//TODO: Fill this in"
  level  = "//TODO: Fill this in"
  write_to = [//TODO: Fill this in]
}

loki.relabel "alloy_logs" {
   forward_to = [//TODO: Fill this in]

    rule {
        target_label = "//TODO: Fill this in"
        replacement = "//TODO: Fill this in"
    }

    rule {
        target_label = "//TODO: Fill this in"
        replacement = "//TODO: Fill this in" 
    }
}

loki.write "mythical" {
    endpoint {
       url = "//TODO: Fill this in"
    } 
}
```
#### Tasks

`logging` block:
- set the log format to "logfmt"
- set the log level to "debug"
- send the logs to the receiver of the`loki.relabel.alloy_logs` component

`loki.relabel` component:
- set the `group` label to "infrastructure"
- set the `service` label to "alloy"
- forward the logs to the receiver of the `loki.write.mythical` component

`loki.write` component:
- export the logs to a locally running Loki database ("http://loki:3100/loki/api/v1/push")

<img width="1874" height="1053" alt="image" src="https://github.com/user-attachments/assets/649fe505-e3a6-4a74-b998-f00975f9d040" />

#### Reloading the config

Whenever we make changes to the file, we must reload the config. 

To reload Alloy's config, hit the following endpoint in a browser or with a tool like `curl`:

```bash
curl -X POST http://localhost:12345/-/reload
```

If the config is valid, you should see a response like the following:

```
config reloaded
```

#### Verification

Navigate to the [Dashboards](http://localhost:3000/dashboards) page and select the `Section 1 Verification` dashboard.

You should see the panels populated with data, showing the number of logs being sent by Alloy as well as the logs themselves.

<img width="911" alt="image" src="https://github.com/user-attachments/assets/07d04e94-caa5-4316-92dc-a50ebfdb333a" />

Expand a log line to view its labels. 

You should see labels "group = infrastructure" and "service = alloy".

### Section 2: Build a pipeline for infrastructure metrics with Grafana Alloy Part I

#### Objectives

- Use the [discovery.http](https://grafana.com/docs/alloy/latest/reference/components/discovery/discovery.http/) component to discover the targets to scrape
- Scrape the targets' metrics using the [`prometheus.scrape`](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.scrape/) component
- Use [`prometheus.remote_write`](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.remote_write/)to write the metrics to the locally running Mimir

We are going to introduce a new component called service discovery (`discovery.http`). 

When you are observing your infrastructure/applications, it's likely that you are working with a dynamic environment.
<img width="907" alt="image" src="https://github.com/user-attachments/assets/f420f7c3-87c6-40c6-9be4-d594aa498338" />


There could be 1000 servers going up and down whose names and addresses you don't know.
<img width="908" alt="image" src="https://github.com/user-attachments/assets/fe1aae3a-4552-4c1a-8c34-6d05e18b1be6" />

You want to avoid having to manage this ever-changing list of things to scrape and get metrics from yourself.

For example, let's say you are working with Amazon instances. Instead of hard coding all the names and addresses, you could reach out to an Amazon endpoint and have it find all of the instances for you and expose those as targets so alloy could scrape it.

#### Instructions

Open `config.alloy` in your editor and copy the following code into it:

```alloy
//Section 2
discovery.http "service_discovery" {
    url = "//TODO: Fill this in"
    refresh_interval = "2s"
}

prometheus.scrape "infrastructure" {
    scrape_interval = "2s"
    scrape_timeout  = "2s"

    targets    = //TODO: Fill this in
    forward_to = [//TODO: Fill this in]
}

prometheus.remote_write "mimir" {
   endpoint {
    url = "//TODO: Fill this in"
   }
}
```

In this section, we will be using the `discovery.http` component to ping an HTTP within our lab environment in charge of finding targets: "http://service-discovery/targets.json"

This http endpoints are aware of all instances of loki, tempo, mimir, and pyroscope databases that are currently running within our environment

We will use a `prometheus.scrape` component to scrape metrics from the discovered targets.

As a last step, we will configure the `prometheus.remote_write` component to write the metrics to a local Mimir database ("http://mimir:9009/api/v1/push")

<img width="912" alt="image" src="https://github.com/user-attachments/assets/845a4274-65e4-46da-868b-0fb71a8f92be" />

Don't forget to [reload the config](#reloading-the-config) after finishing.

#### Verification

Navigate to the [Dashboards](http://localhost:3000/dashboards) page and select the `Section 2 Verification` dashboard.

You should see an `up` value of 1 for the Loki, Mimir, Tempo, and Pyroscope services.

<img width="911" alt="image" src="https://github.com/user-attachments/assets/a7f7d7f8-e0d8-4cc2-b76a-c0d03e55d8d5" />

### Section 3: Build a pipeline for infrastructure metrics with Grafana Alloy Part II

#### Objectives

- Expose metrics from the Postgres DB using the [`prometheus.exporter.postgres](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.exporter.postgres/) component
- Collect metrics from Postgres using the [`prometheus.scrape`](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.scrape/) component
- Use the [`prometheus.relabel`](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.relabel/) to 
  - add the `group="infrastructure"` and `service="postgres"` labels
  - replace the value of 'instance' label for a value that matches the regex ("^postgresql://([^/]+)")
- [Write](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.remote_write/) the metrics to Mimir

#### Instructions

Open `config.alloy` in your editor and copy the following code into it:

```alloy
//Section 3
prometheus.exporter.postgres "mythical" {
    data_source_names = ["postgresql://postgres:mythical@mythical-database:5432/postgres?sslmode=disable"]
}

prometheus.scrape "postgres" {
    scrape_interval = "2s"
    scrape_timeout  = "2s"

    targets    =  //TODO: Fill this in
    forward_to =  [//TODO: Fill this in]
}

prometheus.relabel "postgres" {
    forward_to =  [//TODO: Fill this in]

    rule {
        target_label = "//TODO: Fill this in"
        replacement  = "//TODO: Fill this in"
    }
    
    rule {
        target_label = "//TODO: Fill this in"
        replacement  = "//TODO: Fill this in"
    }

 //What we have: postgres_table_rows_count{instance="postgresql://mythical-database:5432/postgres"}
 //What we want: postgres_table_rows_count{instance="mythical-database:5432/postgres"}
    
    rule {
        // Replace the targeted label.
        action        = "//TODO: Fill this in"

        // The label we want to replace is 'instance'.
        target_label  = "//TODO: Fill this in"

        // Look in the existing 'instance' label for a value that matches the regex.
        source_labels = ["//TODO: Fill this in"]
        regex         = "^postgresql://(.+)"
        
        // Use the first value found in the 'instance' label that matches the regex as the replacement value.
        replacement   = "$1"
    }
}
```

For the `prometheus.scrape` component, we want to scrape the `prometheus.exporter.postgres.mythical` component's targets and forward the metrics to the `prometheus.relabel.postgres` component's receiver.

For the `prometheus.relabel` component, we want to add the `group="infrastructure"` and `service="postgres"` labels to the metrics.

We also want to modify the `instance` label to clean it up. The regex `"^postgresql://(.+)"` will extract the value after `postgresql://`.

<img width="909" alt="image" src="https://github.com/user-attachments/assets/41d4f468-62c3-46cd-8694-efa2424049c2" />

Don't forget to [reload the config](#reloading-the-config) after finishing.

#### Verification

Navigate to [Dashboards](http://localhost:3000/dashboards) > `Section 3 Verification` and you should see a dashboard populating with Postgres metrics. 
You should also see an instance value of `mythical-database:5432/postgres` instead of `postgresql://mythical-database:5432/postgres`.

<img width="910" alt="image" src="https://github.com/user-attachments/assets/5907b198-b732-4b7d-a0a5-65dcf47f7e4c" />

### How to use the Alloy UI to debug pipelines

Alloy UI is a useful tool that helps you visualize how Alloy is configured and what it is doing so you are able to debug efficiently. 

Navigate to `localhost:12345` to see the list of components (orange box) that alloy is currently configured with.
Click on the blue ‘view’ button on the right side (red arrow).
<img width="914" alt="image" src="https://github.com/user-attachments/assets/5f4ac3f7-ab05-43f2-9840-0bac97a59fdd" />

You will see details (green box) about what this component is configured with and what it is exporting.
You can also access the links to view the documentation (orange arrow) for the component and the live debugging feature (yellow arrow). 
<img width="907" alt="image" src="https://github.com/user-attachments/assets/84934f68-4964-4203-9dd5-47693d1a7505" />

Navigate to the ‘Graph’ tab (blue arrow) to access the graph of components and how they are connected.

The number (red box) shown on the dotted lines shows the rate of transfer between components. The window at the top (orange box) configures the interval over which alloy should calculate the per-second rate, so a window of ‘10’ means that alloy should look over the last 10 seconds to compute the rate.

The color of the dotted line signifies what type of data are being transferred between components. See the color key (purple box) for clarification. 

<img width="910" alt="image" src="https://github.com/user-attachments/assets/95b20759-971f-410d-9598-d5db3213eef7" />

# Application Observability 
## Collect, transform, and export application metrics, traces, and logs
### Section 4: Build a pipeline for application metrics with Grafana Alloy

#### Objectives

- Collect metrics from the Mythical services using the [`prometheus.scrape`](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.scrape/) component
- [Write](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.remote_write/) metrics to locally running Mimir using the [`prometheus.write.queue`](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.write.queue/) component

#### Instructions

Open `config.alloy` in your editor and copy the following code into it:

```alloy
//Section 4
prometheus.scrape "mythical" {
    scrape_interval = "2s"
    scrape_timeout  = "2s"

    targets    =  [
        {"__address__"= "//TODO: Fill this in", group = "//TODO: Fill this in", service = "//TODO: Fill this in"},
        {"//TODO: Fill this in"}, 
        ]
    forward_to =  [//TODO: Fill this in]
}

prometheus.write.queue "experimental" {
    endpoint "mimir" {
        url = "//TODO: Fill this in"
    }
}

```
For the `prometheus.scrape` component, we can define scrape targets for mythical services directly by creating a scrape object. Scrape targets are defined as a list of maps, where each map contains a `__address__` key with the address of the target to scrape. 

Any non-double-underscore keys are used as labels for the target.
For example, the following scrape object will scrape Mimir's metrics endpoint and add `env="demo"` and `service="mimir"` labels to the target:

```alloy
targets = [{"__address__" = "mimir:9009",  env = "demo", service = "mimir"}]
```

For this exercise, create two targets using the following addresses. 

- "mythical-server:4000"
- "mythical-requester:4001"

Add the following labels for each target. 
- mythical-server:
  - group = "mythical", service = "mythical-server"
- mythical-requester:
  - group = "mythical", service = "mythical-requester"

Forward the metrics to the `prometheus.write.queue` component we will define next. 

`prometheus.write.queue` component writes metrics to the url of the database we specify. 

Similar to `prometheus.remote_write` component, we use the `endpoint` block we label as "mimir". 
We set the `url` equal the address of the locally running Mimir: "http://mimir:9009/api/v1/push"

<img width="915" alt="image" src="https://github.com/user-attachments/assets/6c7ebcef-c963-41d6-ba6d-a5805c8104d6" />

Don't forget to [reload the config](#reloading-the-config) after finishing.

#### Verification

Navigate to Dashboards > `Section 4 Verification` and you should see a panel with the request rate per beast flowing!

<img width="909" alt="image" src="https://github.com/user-attachments/assets/e3271544-b277-4114-a969-733ce4da064b" />

### Section 5: Build a pipeline for application traces with Grafana Alloy

#### Objectives

- [Receive](https://grafana.com/docs/alloy/latest/reference/components/otelcol/otelcol.receiver.otlp/) spans from the Mythical services and Beyla
- [Batch spans](https://grafana.com/docs/alloy/latest/reference/components/otelcol/otelcol.processor.batch/) for efficient processing
- [Write](https://grafana.com/docs/alloy/latest/reference/components/otelcol/otelcol.exporter.otlp/) the spans to a local instance of Tempo

#### Instructions

Open `config.alloy` in your editor and copy the following code into it:

```alloy
//Section 5
otelcol.receiver.otlp "otlp_receiver" {
    grpc {
        endpoint = "//TODO: Fill in the default value shown in the grpc block section of the otelcol.receiver.otlp doc"
    }
    http {
        endpoint = "//TODO: Fill in the default value shown in the http block section of the otelcol.receiver.otlp doc"
    }
    output {
        traces = [
            //TODO: Fill this in,
        ]
    }
}

otelcol.processor.batch "default" {
    output {
        traces = [
            //TODO: Fill this in,
            ]
    }

    send_batch_size = //TODO: Fill this in 
	  send_batch_max_size = //TODO: Fill this in

	  timeout = "//TODO: Fill this in"
}

otelcol.exporter.otlp "tempo" {
    client {
        endpoint = "//TODO: Fill this in"

        // This is a local instance of Tempo, so we can skip TLS verification
        tls {
            insecure             = true
            insecure_skip_verify = true
        }
    }
}


```
`otelcol.receiver.otlp`

- To configure the `otelcol.receiver.otlp` component, open the doc for the [otelcol.receiver.otlp](https://grafana.com/docs/alloy/latest/reference/components/otelcol/otelcol.receiver.otlp/) component
- Find the default port for grpc and set its endpoint equal to it.
- Find the default port for http and set its endpoint equal to it. 
- Using the `output` block, send the traces to the input of the `otelcol.processor.batch` component we will define next. 

`otecol.processor.batch`

- The batch processor will batch spans until a batch size or a timeout is met, before sending those batches on to another component. 
- Let's configure it to batch minimum 1000 spans, up to 2000 spans, or until 2 seconds have elapsed.
- Using the `output` block, send the batched traces to the input of the `otelcol.exporter.otlp` component we will define next.

`otelcol.exporter.otlp`

- Using the `client` block, write batches of spans to a local instance of Tempo
- The Tempo url is "http://tempo:4317".

<img width="915" alt="image" src="https://github.com/user-attachments/assets/1e3dedbe-d69b-47b6-b7e0-ee3a2ae740e7" />

Don't forget to [reload the config](#reloading-the-config) after finishing.

#### Verification

Navigate to [Dashboards](http://localhost:3000/dashboards) > `Section 5 Verification` and you should see a dashboard with a populated service graph, table of traces coming from the mythical-requester, and the rate of span ingestion by Tempo

<img width="917" alt="image" src="https://github.com/user-attachments/assets/564236f6-e3b5-430c-a963-2f7509960e5c" />

You can also navigate to [Dashboards](http://localhost:3000/dashboards) > `MLT Dashboard`. These dashboards are configured to use the metrics
from Spanmetrics, so you should see data for the spans we're ingesting.

<img width="914" alt="image" src="https://github.com/user-attachments/assets/d0822e32-0af2-4f13-b6de-2c037d2e8a93" />

### Section 6: Build a pipeline for application logs with Grafana Alloy
#### Objectives

- [Ingest](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.source.api/) the logs that are being sent by the mythical services to port 3100
- [Add](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.process/) a `service=”mythical”` label to logs
- [Use](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.process/) `stage.regex` and `stage.timestamp` to extract the timestamp from the log lines and set the log’s timestamp

<img width="914" alt="image" src="https://github.com/user-attachments/assets/d9c8dbc0-29ed-460b-b487-8440075cec59" />
<img width="913" alt="image" src="https://github.com/user-attachments/assets/8b8afaa5-ade1-4c5a-9935-6ccb607af0f9" />

#### Instructions

Open `config.alloy` in your editor and copy the following code into it:

```alloy
//Section 6
loki.source.api "mythical" {
     http {
        listen_address = "0.0.0.0"
        listen_port    = "3100"
    }
    forward_to = [//TODO: Fill this in]
}

loki.process "mythical" {
    stage.static_labels {
        values = {
           //TODO: Fill this in = "//TODO: Fill this in",        
        }
    }
   stage.regex {
        expression=`^.*?loggedtime=(?P<loggedtime>\S+)`
   }

   stage.timestamp {
        source = "//TODO: Fill this in"
        format = "2006-01-02T15:04:05.000Z07:00"
    }

    forward_to = [loki.write.mythical.receiver]
}
```

- Ingest application logs sent from the mythical services using the [`loki.source.api`](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.source.api/) component
- Use the [`loki.process`](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.process/) component to:
  - add a static `service="mythical" label
  - extract the timestamp from the log line using `stage.regex` with this regex: `^.*?loggedtime=(?P<loggedtime>\S+)`
  - set the timestamp of the log to the extracted timestamp
  - Forward the processed logs to Loki
#### Verification

Navigate to [Dashboards](http://localhost:3000/dashboards) > `Section 6 Verification` and you should see a dashboard with the rate of logs coming from the mythical apps as well as panels showing the logs themselves for the server and requester

<img width="913" alt="image" src="https://github.com/user-attachments/assets/01b5718b-aa1c-47d6-92a1-206aca81066c" />

### Section 7: Generate logs from application traces with Grafana Alloy

#### Objectives

- Take the traces we're already ingesting and [convert them to logs (spanlogs)](https://grafana.com/docs/alloy/latest/reference/components/otelcol/otelcol.connector.spanlogs/)
- [Convert](https://grafana.com/docs/alloy/latest/reference/components/otelcol/otelcol.exporter.loki/) the logs to Loki-formatted log entries and forward them to the `loki.processor`. 
- Use [`loki.process`](https://grafana.com/docs/alloy/latest/reference/components/loki/loki.process/) to convert the format and add attributes to the logs
- Forward the processed logs to Loki

#### Instructions

Open `config.alloy` in your editor and copy the following code into it:

```alloy
//Section 7
otelcol.connector.spanlogs "autologging" {
    roots = // TODO: Fill this in
    spans = // TODO: Fill this in
    processes = // TODO: Fill this in

    span_attributes = ["// TODO: Fill this in", "// TODO: Fill this in", "// TODO: Fill this in"]
    //these are the span attributes that I would like to include in the logs

    output {
    logs = [// TODO: Fill this in]
  }
}

otelcol.exporter.loki "autologging" {
    forward_to = [// TODO: Fill this in]
}

// The Loki processor allows us to accept a Loki-formatted log entry and mutate it into
// a set of fields for output.
loki.process "autologging" {
    stage.json {
       expressions = {"body" = ""}
    }

    stage.output {
       source = "body"
    }

    stage.logfmt {
        mapping = {
            http_method_extracted = "// TODO: Fill this in",
            http_status_code_extracted = "// TODO: Fill this in", 
            http_target_extracted = "// TODO: Fill this in", 

        }
    }

    stage.labels {
        values = {
            method = "// TODO: Fill this in", 
            status = "// TODO: Fill this in",
            target = "// TODO: Fill this in", 
        }
    }

    forward_to = [// TODO: Fill this in]
}
```
**`otelcol.connector.spanlogs`**

For the `otelcol.connector.spanlogs` component to work, we will need to forward the spans from the `otelcol.receiver.otlp`'s output > traces we have defined in section 5 to the `otelcol.connector.spanlogs`'s input.

We'd like to make sure to only generate a log for each full trace(root), not for each span or process (that would be a lot of logs!).

We should also make sure to include the `http.method`,`http.status_code`, `http.target` attributes in the logs.

Then send the generated logs to the `otelcol.exporter.loki`'s input. 

**`otelcol.exporter.loki`** 

This component accepts OTLP-formatted logs from other otelcol components and converts them to Loki-formatted log entries without further configuration. 

Forward the Loki-formatted logs to the `loki.process "autologging"`'s receiver for further processing. 

**`loki.process`**

Use this component to:
  - Convert the body from JSON to logfmt using the `stage.json` and `stage.logfmt` stages
  - Add the `method`, `status`, and `target` labels from the `http.method`, `http.status_code`, and `http.target` attributes

<img width="917" alt="image" src="https://github.com/user-attachments/assets/10aaff15-6561-4c6a-b21b-9d1f2a2d5be5" />

Don't forget to [reload the config](#reloading-the-config) after finishing.

#### Verification

Navigate to Dashboards > `Section 7 Verification` and you should see a dashboard with panels containing the rate of spanlog ingestion as well as the spanlogs themselves.

<img width="910" alt="image" src="https://github.com/user-attachments/assets/07cea252-4ba4-489b-957f-eaaeccb07418" />

<img width="911" alt="image" src="https://github.com/user-attachments/assets/fa6b332e-9f32-4844-8213-263f68427ba3" />

# Hands-on Exercises
### Mission 1

#### Description

One of our trusted informants has stashed an encrypted file—`secret_message.txt.enc`—on a remote dead-drop.
This filel can be found within the mission repo. 

The decryption key? Hidden in plain sight, embedded in an internal label on the service discovery targets.
Since internal labels are stripped before metrics make it to Mimir, this covert tactic kept the key out of enemy hands.

Your mission: use Alloy to uncover the hidden key, decrypt the message, and reveal the intel within.

#### Objectives

- Use the Alloy UI to find the key hidden in the internal label on the service discovery targets
- Decode the key and decrypt the secret message

#### Instructions

Access the [Alloy UI](http://localhost:12347) and look for the hidden key on one of the service discovery targets.

To decrypt and print the AES-256-CBC encrypted secret message, run the following command in the terminal at the root of the lab repo directory, using the key you just found:
`openssl enc -aes-256-cbc -d -salt -pbkdf2 -in secret_message.txt.enc -k '<key>'`

#### Verification

You should see the secret message in the console!

### Mission 2

#### Description

A rogue actor has tampered with IMF's monitoring systems, slipping a high-cardinality instance_id label into a metric that counts database calls.

This unexpected spike in cardinality is putting Mimir under serious pressure -- and it's up to us to defuse the situation before it blows.

You can see the dashboard that informed the IMF that this was happening by navigating to [Dashboards](http://localhost:3000/dashboards) > `Mission 2`.

But it's not all bad news. Hidden within the instance_id is valuable intel: the name of the cloud provider.
IMF wants us to extract that information and promote it to a dedicated cloud_provider label—transforming this mess into a mission success.

IMF has equipped you with the following regex to help you complete this mission:
`^(aws|gcp|azure)-.+`

#### Objectives

- Using `prometheus.relabel`, use the provided regex to replace the `cloud_provider` label with the extracted value from the `instance_id` label.
- Drop the `instance_id` label.

#### Instructions

For this exercise, you may find the following components useful:

- [prometheus.relabel](https://grafana.com/docs/alloy/latest/reference/components/prometheus/prometheus.relabel/)

Go back to the portion of config from Section 4, where we started scraping metrics from the mythical services. Paste the following in above the `prometheus.write.queue` component (**note**: the order of components does not matter, this is just for organization and readability):

```alloy
prometheus.relabel "mission_2" {
    forward_to = [prometheus.write.queue.experimental.receiver]

  //write a relabel rule to extract the cloud provider from the instance_id label and add it as a new label called cloud_provider
    rule {
        action        = "// TODO: Fill this in"
        target_label  = "// TODO: Fill this in"
        source_labels = ["// TODO: Fill this in"]
        regex         = "^(aws|gcp|azure)-.+"
        replacement   = "$1"
    }

    // drop the instance_id label from metrics
    rule {
        action  = "// TODO: Fill this in"
        regex   = "// TODO: Fill this in"
    }
}
```

#### Verification

Navigate to the [Explore](http://localhost:3000/explore) page and look at the metrics.
Query for `count by (cloud_provider) (rate(mythical_db_request_count_total [$__rate_interval]))` and you should see a non-zero value.

<img width="909" alt="image" src="https://github.com/user-attachments/assets/7a2fc73e-03ea-4e5c-be12-e4053027172c" />

### Mission 3

After much debate, the various departments within IMF have reached a rare consensus: it's time to standardize the attribute name for service tiers.
Until now, teams have been using conflicting keys like `servicetier` and `tier`, creating chaos in spanmetrics and cross-department dashboards.

Headquarters has spoken: `service.tier` is the new standard.

Your mission: use Alloy to bring order to the data.
Standardize the attribute across the board so that spanmetrics flow smoothly and dashboards speak a common language.

#### Objectives

- Use the [`otelcol.processor.attributes`](https://grafana.com/docs/agent/latest/flow/reference/components/otelcol.processor.attributes/) component to set the `service.tier` attribute to the value of
  the `servicetier` or `tier` attributes.
- Drop the `servicetier` and `tier` attributes.

#### Instructions

The [`otelcol.processor.attributes`](https://grafana.com/docs/alloy/latest/reference/components/otelcol/otelcol.processor.attributes/) component allows you to add, set, or drop attributes.

Go back to the portion of config from Section 5, where we received traces from the mythical services. Paste the following  above the `otelcol.processor.batch.default` component (**note**: the order of components does not matter, this is just for organization and readability):

```alloy
otelcol.processor.attributes "mission_3" {
    // These two actions are used to add the service.tier attribute to spans from
    // either the servicetier or tier attributes.
    action {
        action         = "//TODO: Fill this in"
        key            = "//TODO: Fill this in"
        from_attribute = "//TODO: Fill this in"
    }
    action {
        action         = "//TODO: Fill this in"
        key            = "//TODO: Fill this in"
        from_attribute = "//TODO: Fill this in"
    }

    // This isn't required, but shows how to exclude the attributes we just copied.
    exclude {
        match_type = "strict"

        attribute {
            key = "//TODO: Fill this in"
        }

        attribute {
            key = "//TODO: Fill this in"
        }
    }

    output {
        traces = [otelcol.processor.batch.default.input]
    }
}
```

#### Verification

Navigate to [Dashboards](http://localhost:3000/dashboards) > `Mission 3` and you should see a dashboard with data including the new `service_tier` label, which came from spanmetrics generation using the `service.tier` attribute we just consolidated.

<img width="909" alt="image" src="https://github.com/user-attachments/assets/db5b980b-83b1-4c92-9d19-b33e50a52530" />


### Mission 4

#### Description

The IMF needs your expertise for one final mission.
An opposing state actor exploited a Zero-Day vulnerability in one of our servers, causing sensitive tokens to be logged by the mythical-requester.

The security team is standing by, but before they can act, we need to make sure no tokens are being written to Loki.
Your task: use Alloy to identify and redact any sensitive tokens from the mythical-service logs—effectively, clean up the trail and keep things secure.

Navigate to [Dashboards](http://localhost:3000/dashboards) > `Mission 4`. You will see logs coming in with sensitive token information. 

#### Objectives

- Redact any tokens found in the logs from the mythical services

#### Instructions

Take a look at the [`loki` components](https://grafana.com/docs/alloy/latest/reference/components/loki/). Are there any that seem like they could be useful for this mission?

Which section would you add this component to and how would you have to change the previous configuration? 

#### Verification

Navigate to [Dashboards](http://localhost:3000/dashboards) > `Mission 4` and you should see a dashboard with a
panel showing the rate of logs with tokens coming from the mythical services as well as the logs themselves with the secret token redacted. 

<img width="913" alt="image" src="https://github.com/user-attachments/assets/02151116-d8c5-4aa1-844a-6c6d9a32285a" />

<img width="912" alt="image" src="https://github.com/user-attachments/assets/4f066278-ba62-4a0e-b905-75d1c4f25a34" />
<img width="912" alt="image" src="https://github.com/user-attachments/assets/ae9e8f4a-9fcc-435d-bbf6-7b482b01c87a" />
<img width="915" alt="image" src="https://github.com/user-attachments/assets/ed565c8c-31e8-47f6-bc20-893e73b70eb6" />
<img width="913" alt="image" src="https://github.com/user-attachments/assets/15e5a2cb-0e8f-46f0-b93e-4e32e27b992d" />
