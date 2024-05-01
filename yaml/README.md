| NAME                    | PROMPT                          | DESCRIPTION                                                    | EXAMPLE                                                 |
| ----------------------- | ------------------------------- | -------------------------------------------------------------- | ------------------------------------------------------- |
| app.yaml                | Create Application Config       | the basic schema of a Kubernetes application                   | [app.yaml](yaml/app.yaml)                               |
| app-livenessProbe.yaml  | Add Liveness Probe              | a liveness probe for your application                          | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)   |
| app-readinessProbe.yaml | Add Readiness Probe             | a readiness probe for your application                         | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml   | Configure Volume Mounts         | and configure storage volumes for your application             | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml)     |
| app-cronjob.yaml        | Create Cron Job                 | a cron job within your application                             | [app-cronjob.yaml](yaml/app-cronjob.yaml)               |
| app-job.yaml            | Create a Job                    | a job within your application                                  | [app-job.yaml](yaml/app-job.yaml)                       |
| app-multicontainer.yaml | Set Up Multi-container Pods     | a pod that runs more than one container                        | [app-multicontainer.yaml](yaml/app-multicontainer.yaml) |
| app-resources.yaml      | Configure Resource Usage        | to configure resource requests and limits for your application | [app-resources.yaml](yaml/app-resources.yaml)           |
| app-secret-env.yaml     | Set Up Secrets as Env Variables | environment variables using secrets                            | [app-secret-env.yaml](yaml/app-secret-env.yaml)         |

