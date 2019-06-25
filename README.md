# GCP-Infra
You can build this infrastructure with the deployment tool included in the SDK for Google-Cloud.

= Details =

The yaml file will generate:

 - A VM under the name "my-vm".
 -- type: compute.v1.instance
 -- zone: it would be a var "ZONE" you can set it to your prefered value.
 -- startup-script: A single update of the system.

 - Disk boot
 -- type: persistent
 -- image: debian-9-stretch-v20180806

 - Basic Network.
