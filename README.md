# myproxy
nginx proxy app used for request tracing TOI

This app is a basic nginx proxy that simply proxies requests from itself to the host defined in the environment DESTINATION_HOST.<br>

The app in this repo has a nginx setting that will limit bandwidth by via limit_rate in the nginx.conf file to simulate a bottlenecked network hop. If you need to remove the bottleneck, just comment out the *limit_rate* section in nginx.conf.
