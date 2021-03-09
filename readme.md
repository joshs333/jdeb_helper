# Jdeb_helper
A quick tool I put together to generate debian files from a configuration yaml.

Not sure if I'll actually use it. At best it makes my life more convient when making debians. At worst- it's notes on how to make a debian lol. We'll see what happens.

Big thanks to: https://github.com/streadway/hello-debian

The changelog can go in the debian info file... or a separate file that you can pass with the `--changelog` argument (file looks like the below)
```
- type: "stable"
  version: "0.0.2-1"
  stamp: "Mon, 8 Mar 2021 17:05:35 +0100"
  messages:
  - "Add commas, test addition."
- type: "stable"
  version: "0.0.1-1"
  stamp: "Mon, 8 Mar 2021 16:05:35 +0100"
  messages:
  - "Base build"
  ```