# Troubleshooting

If you're having trouble with running Alldocs, here is a quick guide to solve most common problems.

> Most faults about the Instance is closely related to the Instance provider, Cloud Platform. Provided you're sure the fault is caused by Cloud Platform, refer to [Cloud Platform Documentation](https://support.websoft9.com/docs/faq/tech-instance.html).

#### How can I check the error logs?

You can find the keywords **Failed** or **error** from the logs directory: `/data/logs`

#### Can't start Alldocs service?

Insufficient disk space and memory, incorrect configuration file may cause the failure to start the service. 

It is recommended to first check through the command.

```shell
# restart Alldocs service
systemctl status alldocs
journalctl -u alldocs

# view disk space
df -lh

# view memory rate
free -lh
```

#### Error in Chrome when modify password?

This error has nothing to do with Alldocs server. Just upgrade you local Chrome to solve it.

![chrome error of Alldocs](https://libs.websoft9.com/Websoft9/DocsPicture/zh/alldocs/alldocs-chromeerror-websoft9.png)
