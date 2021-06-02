# envoy-munin

Enphase IQ Envoy Munin voltage and other stats

Copy the plugin to your munin node/server's /etc/munin/plugins and restart
`munin-node`. The plugin requires that `curl` and `jq` are installed and
`envoy.local` resolves to the IQ Envoy device on your (home) network.
