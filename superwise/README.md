# Superwise Integration

## Overview
[Superwise][1] provides model observability for high-scale machine learning (ML) operations.
Superwise's model observability gives you visibility and context into your models' behaviors, so you can easily monitor model risks based on different use cases. With Superwise, data scientists, ML engineers, and business ops get model observability without alert fatigue, so you can be confident about your model management.  
    

![Superwise Dashboard]( https://raw.githubusercontent.com/DataDog/integrations-extras/master/superwise/images/5.png)  

Superwise’s model metrics and incidents integration sends out-of-the-box model metrics, including drift, activity, incidents, and custom metrics, directly to Datadog. You’ll get an overview of which models are misbehaving that can be tailored to any use case, logic, segmentation, threshold, and sensitivity.


## Setup

With the Datadog integration configured in Superwise, standard model metrics are sent to Datadog, and users get model observability dashboards in Datadog. You can configure any specific model metric and incident policy, and send them to Datadog for model observability that is tailored to your use case.

1. Go to [Superwise portal][2] and select **Integrations**.

2. Click **Create a new channel** and select **Datadog**.
![Superwise Integration]( https://raw.githubusercontent.com/DataDog/integrations-extras/master/superwise/images/2.png)

3. Input your Datadog API Key and Application key, and click **Test**. A test request is sent to your Datadog account to validate the integration. If the request was successfully sent, there is a message in Superwise saying the test was delivered successfully. To finish the setup, click **Create channel**.

![Superwise Integration]( https://raw.githubusercontent.com/DataDog/integrations-extras/master/superwise/images/6.png)

3. That's it, now you can see the new Datadog integration widget.
![Superwise Integration]( https://raw.githubusercontent.com/DataDog/integrations-extras/master/superwise/images/3.png)

### Validation
In Datadog, go to **Metrics Explorer** and search for the metric `superwise.integration.test` to verify that the integration between Superwise and Datadog is working. 
![Superwise Integration]( https://raw.githubusercontent.com/DataDog/integrations-extras/master/superwise/images/4.png)   

## Data Collected

### Metrics

See [metadata.csv][3] for a list of metrics provided by this check.

### Events

The Superwise integration does not include any events.

### Service Checks

The Superwise integration does not include any service checks.

## Troubleshooting

Need help? Take a look at [Superwise documentation][4].


[1]: https://www.superwise.ai/
[2]: https://portal.superwise.ai/
[3]: https://github.com/DataDog/integrations-core/blob/master/check/metadata.csv
[4]: https://docs.superwise.ai