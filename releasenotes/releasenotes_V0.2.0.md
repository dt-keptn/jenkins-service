# Release Notes 0.2.0

## New Features
- new Jenkins image: keptn/jenkins:0.5.0

## Fixed Issues
- Jenkins URL removed from Jenkins configuration
- Dynatrace-related environment variables removed from Jenkins configuration
- Hardening the deploy script to check each installation step [#250](https://github.com/keptn/keptn/issues/250)
- Hardening the deploy pipeline to check whether the DT_TENANT_URL is set. Besides, DT deploy event contains additional meta-information [#268](https://github.com/keptn/keptn/issues/268).

## Known Limitations