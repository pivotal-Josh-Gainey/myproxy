# myproxy
nginx proxy app used for request tracing TOI

This app is a basic nginx proxy that simply proxies requests from itself to the host defined in the environment DESTINATION_HOST.<br>

This specific app will limit bandwidth by setting a limit_rate in the nginx config to simulate bottlenecked network hop.
