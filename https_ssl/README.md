# https_ssl

Scripts and HAproxy configuration for HTTPS on the load balancer.

## Files

- 0-world_wide_web: displays information about the subdomains of a domain
- 1-haproxy_ssl_termination: HAproxy configuration with SSL termination
- 2-redirect_http_to_https: HAproxy configuration redirecting HTTP to HTTPS
