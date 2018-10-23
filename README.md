# opsworks_delayed_job

This wrapper provides support custom /etc/hosts entries

Additional /etc/hosts entries can be configured by defining the following JSON attributes:

```
{
    "opsworks": {
        "instance": {
            "custom_dns_entries": [
                {
                    "ip": "xx.x.xxx.xx",
                    "dns_names": "xxxxxxx.com  xxxx.xxxxxxxx.com xxxxxx.com"
                }
            ]
        }
    }
}
```
