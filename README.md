# Характеристики:
| NAME                                        | PROMPT                                                    | DESCRIPTION                                                         | EXAMPLE                                                                              |
|---------------------------------------------|-----------------------------------------------------------|---------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| app.yaml                                    | kubectl ai "create deploy app.yaml where the main image is gcr.io/k8s-test5/demo:v1.0.0"                  | -                                                                 |  https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app.yaml                                  |
| app-livenessProbe.yaml                      | kubectl ai "create deploy app-livenessProbe.yaml"                                                         | -                                                                  | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-livenessProbe.yaml                                                                                    | 
| app-readinessProbe.yaml                     | kubectl ai "create deploy app-readinessProbe.yaml"                                                        | -                                                                  | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-readinessProbe.yaml                                                                                    |
| app-volumeMounts.yaml                       | kubectl ai "create deploy app-volumeMounts.yaml"                                                          | -                                                                  | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-volumeMounts.yaml                                                                                    | 
| app-cronjob.yaml                            | kubectl ai "create deploy app-cronjob.yaml with on failure restart policy "                               | -                                                                  | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-cronjob.yaml                                                                                    | 
| app-job.yaml                                | kubectl ai "create deploy app-job.yaml where the main image is gcr.io/k8s-test5/demo:v1.0.0"              | -                                                                  | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-job.yaml                                                                                    | 
| app-multicontainer.yaml                     | kubectl ai "create deploy app-multicontainer.yaml where the main image is gcr.io/k8s-test5/demo:v1.0.0"   | -                                                                    | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-multicontainer.yaml       
| app-secret-env.yaml                         | kubectl ai "create deploy app-resources.yaml where the main image is gcr.io/k8s-test5/demo:v1.0.0"        | -                                                                    | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-resources.yaml
| app-resources.yaml                          | kubectl ai "create deploy app-secret-env.yaml which accepts encrypted base64 key as secret"       | -                                                                   | https://raw.githubusercontent.com/gidra39/openai-kubectl/main/yaml/app-secret-env.yaml |   
