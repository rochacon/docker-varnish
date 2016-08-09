# docker-varnish

Simple Varnish image based on Alpine.

## Example VCL

```
# /etc/varnish/default.vcl
vcl 4.0;

backend default {
  .host = "some.domain.net";
  .port = "80";
}
```
