#  Demo Project

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-black.svg)](https://sonarcloud.io/dashboard?id=piomin_infoshare-gdynia-app-demo)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=piomin_infoshare-gdynia-app-demo&metric=bugs)](https://sonarcloud.io/dashboard?id=piomin_infoshare-gdynia-app-demo)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=piomin_infoshare-gdynia-app-demo&metric=coverage)](https://sonarcloud.io/dashboard?id=piomin_infoshare-gdynia-app-demo)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=piomin_infoshare-gdynia-app-demo&metric=ncloc)](https://sonarcloud.io/dashboard?id=piomin_infoshare-gdynia-app-demo)

In this project I'm demonstrating you the most interesting features of [Backstage](https://backstage.io/) for generating app skeletons.
This skeleton was generated automatically from the following [template](https://github.com/piomin/backstage-templates/blob/master/templates/spring-boot-basic/template.yaml).

Once the app is generated you can run it locally with the following command:
```shell
mvn clean spring-boot:run
```

You can also run it automatically on Podman or OpenShift using the `odo` tool.
The `devfile.yaml` is already in the project root repository. You just need to execute:
```shell
odo dev
```

You can also deploy app to Kubernetes or OpenShift with the Skaffold CLI.
The configuration is already there. Just run:
```shell
skaffold dev
```