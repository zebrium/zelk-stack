# ZELK Stack

* Automatically catch application incidents and see root cause using your Elastic Stack. No manual training, no manual alert rules and no changes to your end points.

* Auto-detected application incidents are displayed in an elegant Kibana dashboard. With just a click, you can view the set of correlated log events that describe the root cause. Thumbs up and down buttons let you provide feedback on incident quality and customize your incident feed.

# How it Works

1. Configure an additional output plugin in your Logstash instance to send log events and metrics to Zebrium.
2. Zebrium's Autonomous Incident Detection and Root Cause will send incident details back to Logstash via a webhook input plugin.
3. Incident summary and drill down into the Incident events in Elasticsearch is available directly from the Zebrium ML-Detected Incidents canvas in Kibana.
4. For advanced drilldown and troubleshooting workflows, simply click on the Zebrium link in the Incident canvas.

# Requirements

* ZELK Stack integrations require the ELK stack including Logstash.
* Secure end-point for the Zebrium outgoing webhook to send Incident details to Logstash/Kibana
  * Uses the [Logstash HTTP Input Plugin](https://www.elastic.co/guide/en/logstash/current/plugins-inputs-http.html) with SSL and Authentication enabled.

# Support

If you need help with this integration, please contact Zebrium by [email](mailto:support@zebrium.com) to support@zebrium.com

# Integration Walkthrough
 
See [ZELK Stack Integration](https://docs.zebrium.com/docs/zelk) for details on configuring ZELK Stack with [Zebrium's Autonomous Incident Detection](https://www.zebrium.com)


