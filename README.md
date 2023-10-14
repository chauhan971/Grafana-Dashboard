# Grafana-Dashboard

<H1>Install Nagios Server on ubuntu </H1>
<p> For installation you can work with AWS or a VM machine Your choice</p>
<p>After Nagios Installation The Next step is to install the Grafana plugin to your Nagios </p>

<H2>Grafana</H2>
<p>Grafana is an open-source, multi-platform analytics and interactive visualization web application. It allows you to query, visualize, alert on, and understand your metrics no matter where they are stored. Grafana provides charts, graphs, and alerts for the web when connected to supported data sources. It's used for running data analytics with the help of metrics that give insight into complex infrastructure and large amounts of data. You can create, explore, and share beautiful dashboards with your team and foster a data-driven culture</p>



<p>After Grafana installation you can access it by using localhost and if working with public ip[ like on aws then publicip:3000</p>

<H2> DATA SOURCE</H2>
<P>Now you need to connect the Nagios server with Grafana and for that simplejson can be used </P>
<p>Simplejson will ask for the server URL and then SAVE&TEST after that you will be able to create your dashboard, run queries for different purposes like 
1. CPU usage
2. Network Latency
3. Network Traffic etc.</p>
