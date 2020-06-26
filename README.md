# postbill

Experimenting with LinkedIn API and ktor OAuth

## set up auto-reload for local development

Configure IntelliJ with a Run/Debug config for this project.  Note the use of `installDist` task and `-t` argument:

![intellij_run_debug_config](https://user-images.githubusercontent.com/38859656/85881513-bad47d80-b7ab-11ea-8c3f-7a47a7348675.png)

Start that task in IntelliJ.  _In intelliJ, run_

```sh
gradle run
```

Use JDK 8 to allow autoreload, as advised by the [ktor docs](https://ktor.io/servers/autoreload.html):

![postbill_sdk](https://user-images.githubusercontent.com/38859656/85881844-49e19580-b7ac-11ea-8e97-134d85f8e628.png)

