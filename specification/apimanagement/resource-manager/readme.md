# ApiManagement

> see https://aka.ms/autorest

This is the AutoRest configuration file for ApiManagement.

---

## Getting Started

To build the SDK for ApiManagement, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`

---

## Configuration

### Basic Information

These are the global settings for the ApiManagement API.

``` yaml
title: ApiManagementClient
description: ApiManagement Client
openapi-type: arm
tag: package-preview-2024-06
```

### Tag: package-preview-2024-06

These settings apply only when `--tag=package-preview-2024-06` is specified on the command line.

```yaml $(tag) == 'package-preview-2024-06'
input-file:
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apigateway.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimallpolicies.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimauthorizationproviders.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimdocumentations.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimgatewayConfigConnections.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimpolicyfragments.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimpolicyrestrictions.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimpolicyrestrictionsvalidation.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimportalconfigs.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimworkspacebackends.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimworkspacecertificates.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimworkspacediagnostics.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimworkspacelinks.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimworkspaceloggers.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/apimworkspaces.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/definitions.json
  - Microsoft.ApiManagement/preview/2024-06-01-preview/operationStatuses.json
```
### Tag: package-2024-05

These settings apply only when `--tag=package-2024-05` is specified on the command line.

```yaml $(tag) == 'package-2024-05'
input-file:
  - Microsoft.ApiManagement/stable/2024-05-01/apigateway.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimallpolicies.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimanagement.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimapis.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimapisByTags.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimapiversionsets.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimauthorizationproviders.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimauthorizationservers.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimbackends.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimcaches.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimcertificates.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimconnectivitycheck.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimcontenttypes.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimdeletedservices.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimdeployment.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimdiagnostics.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimdocumentations.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimemailtemplates.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimgatewayConfigConnections.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimgateways.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimgroups.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimidentityprovider.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimissues.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimloggers.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimnamedvalues.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimnetworkstatus.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimnotifications.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimoutbounddependency.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimpolicies.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimpolicydescriptions.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimpolicyfragments.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimpolicyrestrictions.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimpolicyrestrictionsvalidation.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimportalconfigs.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimportalrevisions.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimportalsettings.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimprivatelink.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimproducts.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimproductsByTags.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimquotas.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimregions.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimreports.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimschema.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimsettings.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimskus.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimsubscriptions.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimtagresources.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimtags.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimtenant.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimusers.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimworkspacebackends.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimworkspacecertificates.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimworkspacediagnostics.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimworkspacelinks.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimworkspaceloggers.json
  - Microsoft.ApiManagement/stable/2024-05-01/apimworkspaces.json
  - Microsoft.ApiManagement/stable/2024-05-01/definitions.json
  - Microsoft.ApiManagement/stable/2024-05-01/operationStatuses.json
tag: package-preview-2024-06
```
### Tag: package-preview-2023-09

These settings apply only when `--tag=package-preview-2023-09` is specified on the command line.

```yaml $(tag) == 'package-preview-2023-09'
input-file:
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimallpolicies.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apigateway.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimauthorizationproviders.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimdocumentations.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimgatewayConfigConnections.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimpolicyfragments.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimpolicyrestrictions.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimpolicyrestrictionsvalidation.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimportalconfigs.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimworkspacebackends.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimworkspacecertificates.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimworkspacediagnostics.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimworkspaceloggers.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimworkspacelinks.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/apimworkspaces.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/definitions.json
  - Microsoft.ApiManagement/preview/2023-09-01-preview/operationStatuses.json
```
### Tag: package-preview-2023-05

These settings apply only when `--tag=package-preview-2023-05` is specified on the command line.

``` yaml $(tag) == 'package-preview-2023-05'
input-file:
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimallpolicies.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimauthorizationproviders.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimdocumentations.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimpolicyfragments.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimpolicyrestrictions.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimpolicyrestrictionsvalidation.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimportalconfigs.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/apimworkspaces.json
  - Microsoft.ApiManagement/preview/2023-05-01-preview/definitions.json
```

### Tag: package-preview-2023-03

These settings apply only when `--tag=package-preview-2023-03` is specified on the command line.

``` yaml $(tag) == 'package-preview-2023-03'
input-file:
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimauthorizationproviders.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimdocumentations.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimpolicyfragments.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimportalconfigs.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/apimworkspaces.json
  - Microsoft.ApiManagement/preview/2023-03-01-preview/definitions.json
```

### Tag: package-preview-2022-09

These settings apply only when `--tag=package-preview-2022-09` is specified on the command line.

``` yaml $(tag) == 'package-preview-2022-09'
input-file:
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimauthorizationproviders.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimdocumentations.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimpolicyfragments.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimportalconfigs.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/apimworkspaces.json
  - Microsoft.ApiManagement/preview/2022-09-01-preview/definitions.json
```

### Tag: package--2022-08

These settings apply only when `--tag=package-2022-08` is specified on the command line.

``` yaml $(tag) == 'package-2022-08'
input-file:
  - Microsoft.ApiManagement/stable/2022-08-01/apimanagement.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimapis.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimapisByTags.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimapiversionsets.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimauthorizationservers.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimauthorizationproviders.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimbackends.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimcaches.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimcertificates.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimconnectivitycheck.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimcontenttypes.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimdeletedservices.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimdeployment.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimdiagnostics.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimemailtemplates.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimgateways.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimgroups.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimidentityprovider.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimissues.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimloggers.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimnamedvalues.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimnetworkstatus.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimnotifications.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimoutbounddependency.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimpolicies.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimpolicydescriptions.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimpolicyfragments.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimportalconfigs.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimportalrevisions.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimportalsettings.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimprivatelink.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimproducts.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimproductsByTags.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimquotas.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimregions.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimreports.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimschema.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimsettings.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimskus.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimsubscriptions.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimtagresources.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimtags.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimtenant.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimusers.json
  - Microsoft.ApiManagement/stable/2022-08-01/definitions.json
  - Microsoft.ApiManagement/stable/2022-08-01/apimdocumentations.json
```

### Tag: package-preview-2022-04

These settings apply only when `--tag=package-preview-2022-04` is specified on the command line.

``` yaml $(tag) == 'package-preview-2022-04'
input-file:
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimauthorizationproviders.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimpolicyfragments.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimportalconfigs.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2022-04-01-preview/definitions.json
```

### Tag: package-preview-2021-12

These settings apply only when `--tag=package-preview-2021-12` is specified on the command line.

``` yaml $(tag) == 'package-preview-2021-12'
input-file:
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimpolicyfragments.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimportalconfigs.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2021-12-01-preview/definitions.json
```

### Tag: package-2021-08

These settings apply only when `--tag=package-2021-08` is specified on the command line.

``` yaml $(tag) == 'package-2021-08'
input-file:
  - Microsoft.ApiManagement/stable/2021-08-01/apimanagement.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimapis.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimapisByTags.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimapiversionsets.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimauthorizationservers.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimbackends.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimcaches.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimcertificates.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimconnectivitycheck.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimcontenttypes.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimdeletedservices.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimdeployment.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimdiagnostics.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimemailtemplates.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimgateways.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimgroups.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimidentityprovider.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimissues.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimloggers.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimnamedvalues.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimnetworkstatus.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimnotifications.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimoutbounddependency.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimpolicies.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimpolicydescriptions.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimportalrevisions.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimportalsettings.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimprivatelink.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimproducts.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimproductsByTags.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimquotas.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimregions.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimreports.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimschema.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimsettings.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimskus.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimsubscriptions.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimtagresources.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimtags.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimtenant.json
  - Microsoft.ApiManagement/stable/2021-08-01/apimusers.json
  - Microsoft.ApiManagement/stable/2021-08-01/definitions.json
```

### Tag: package-preview-2021-04

These settings apply only when `--tag=package-preview-2021-04` is specified on the command line.

``` yaml $(tag) == 'package-preview-2021-04'
input-file:
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimoutbounddependency.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimprivatelink.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimschema.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/apimconnectivitycheck.json
  - Microsoft.ApiManagement/preview/2021-04-01-preview/definitions.json
```

### Tag: package-preview-2021-01

These settings apply only when `--tag=package-preview-2021-01` is specified on the command line.

``` yaml $(tag) == 'package-preview-2021-01'
input-file:
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2021-01-01-preview/definitions.json
```

### Tag: package-2020-12

These settings apply only when `--tag=package-2020-12` is specified on the command line.

``` yaml $(tag) == 'package-2020-12'
input-file:
  - Microsoft.ApiManagement/stable/2020-12-01/apimanagement.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimapis.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimapisByTags.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimapiversionsets.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimauthorizationservers.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimbackends.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimcaches.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimcertificates.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimcontenttypes.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimdeletedservices.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimdeployment.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimdiagnostics.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimemailtemplates.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimgateways.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimgroups.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimidentityprovider.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimissues.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimloggers.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimnamedvalues.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimnetworkstatus.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimnotifications.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimpolicies.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimpolicydescriptions.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimportalrevisions.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimportalsettings.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimproducts.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimproductsByTags.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimquotas.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimregions.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimreports.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimsettings.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimskus.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimsubscriptions.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimtagresources.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimtags.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimtenant.json
  - Microsoft.ApiManagement/stable/2020-12-01/apimusers.json
  - Microsoft.ApiManagement/stable/2020-12-01/definitions.json
```

### Tag: package-preview-2020-06

These settings apply only when `--tag=package-preview-2020-06` is specified on the command line.

``` yaml $(tag) == 'package-preview-2020-06'
input-file:
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimcontenttypes.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimdeletedservices.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimportalrevisions.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimsettings.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimskus.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2020-06-01-preview/definitions.json
```

### Tag: package-2019-12

These settings apply only when `--tag=package-2019-12` is specified on the command line.

``` yaml $(tag) == 'package-2019-12'
input-file:
  - Microsoft.ApiManagement/stable/2019-12-01/apimanagement.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimapis.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimapisByTags.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimapiversionsets.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimauthorizationservers.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimbackends.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimcaches.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimcertificates.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimcontenttypes.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimdeployment.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimdiagnostics.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimemailtemplates.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimgateways.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimgroups.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimidentityprovider.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimissues.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimloggers.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimnamedvalues.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimnetworkstatus.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimnotifications.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimpolicies.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimpolicydescriptions.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimportalsettings.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimproducts.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimproductsByTags.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimquotas.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimregions.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimreports.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimsubscriptions.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimtagresources.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimtags.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimtenant.json
  - Microsoft.ApiManagement/stable/2019-12-01/apimusers.json
  - Microsoft.ApiManagement/stable/2019-12-01/definitions.json
```

### Tag: package-preview-2019-12

These settings apply only when `--tag=package-preview-2019-12` is specified on the command line.

``` yaml $(tag) == 'package-preview-2019-12'
input-file:
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimanagement.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimapis.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimapisByTags.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimapiversionsets.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimauthorizationservers.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimbackends.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimcaches.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimcertificates.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimdeployment.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimdiagnostics.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimemailtemplates.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimgateways.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimgroups.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimidentityprovider.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimissues.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimloggers.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimnetworkstatus.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimnotifications.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimpolicies.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimpolicydescriptions.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimportalsettings.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimproducts.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimproductsByTags.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimnamedvalues.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimquotas.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimregions.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimreports.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimsubscriptions.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimtagresources.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimtags.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimtenant.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/apimusers.json
  - Microsoft.ApiManagement/preview/2019-12-01-preview/definitions.json
```

### Tag: package-2019-01

These settings apply only when `--tag=package-2019-01` is specified on the command line.

``` yaml $(tag) == 'package-2019-01'
input-file:
  - Microsoft.ApiManagement/stable/2019-01-01/apimanagement.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimapis.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimapisByTags.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimapiversionsets.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimauthorizationservers.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimbackends.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimcaches.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimcertificates.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimdeployment.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimdiagnostics.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimemailtemplates.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimgroups.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimidentityprovider.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimissues.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimloggers.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimnetworkstatus.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimnotifications.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimopenidconnectproviders.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimpolicies.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimpolicysnippets.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimportalsettings.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimproducts.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimproductsByTags.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimproperties.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimquotas.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimregions.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimreports.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimsubscriptions.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimtagresources.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimtags.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimtenant.json
  - Microsoft.ApiManagement/stable/2019-01-01/apimusers.json
  - Microsoft.ApiManagement/stable/2019-01-01/definitions.json
```

### Tag: package-2018-06-preview

These settings apply only when `--tag=package-2018-06-preview` is specified on the command line.

``` yaml $(tag) == 'package-2018-06-preview'
input-file:
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimanagement.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimapis.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimapisByTags.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimauthorizationservers.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimbackends.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimcaches.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimcertificates.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimdeployment.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimdiagnostics.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimemailtemplates.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimgroups.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimidentityprovider.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimissues.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimloggers.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimnotifications.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimnetworkstatus.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimopenidconnectproviders.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimpolicies.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimpolicysnippets.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimportalsettings.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimproducts.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimproductsByTags.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimproperties.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimquotas.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimregions.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimreports.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimsubscriptions.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimtagresources.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimtags.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimtenant.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimusers.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/apimapiversionsets.json
- Microsoft.ApiManagement/preview/2018-06-01-preview/definitions.json
```

## Suppression

``` yaml
directive:
  - suppress: R3016
    reason: existing properties, can't be changed without breaking API.
    #where:
    #  - $.definitions.ApiManagementServiceUploadCertificateParameters.properties.certificate_password
    #  - $.definitions.QuotaCounterContract.properties.Value

```

### Tag: package-2018-01

These settings apply only when `--tag=package-2018-01` is specified on the command line.

``` yaml $(tag) == 'package-2018-01'
input-file:
- Microsoft.ApiManagement/stable/2018-01-01/apimanagement.json
- Microsoft.ApiManagement/stable/2018-01-01/apimapis.json
- Microsoft.ApiManagement/stable/2018-01-01/apimauthorizationservers.json
- Microsoft.ApiManagement/stable/2018-01-01/apimbackends.json
- Microsoft.ApiManagement/stable/2018-01-01/apimcertificates.json
- Microsoft.ApiManagement/stable/2018-01-01/apimdeployment.json
- Microsoft.ApiManagement/stable/2018-01-01/apimdiagnostics.json
- Microsoft.ApiManagement/stable/2018-01-01/apimemailtemplate.json
- Microsoft.ApiManagement/stable/2018-01-01/apimgroups.json
- Microsoft.ApiManagement/stable/2018-01-01/apimidentityprovider.json
- Microsoft.ApiManagement/stable/2018-01-01/apimloggers.json
- Microsoft.ApiManagement/stable/2018-01-01/apimnotifications.json
- Microsoft.ApiManagement/stable/2018-01-01/apimnetworkstatus.json
- Microsoft.ApiManagement/stable/2018-01-01/apimopenidconnectproviders.json
- Microsoft.ApiManagement/stable/2018-01-01/apimportalsettings.json
- Microsoft.ApiManagement/stable/2018-01-01/apimproducts.json
- Microsoft.ApiManagement/stable/2018-01-01/apimproperties.json
- Microsoft.ApiManagement/stable/2018-01-01/apimquotas.json
- Microsoft.ApiManagement/stable/2018-01-01/apimreports.json
- Microsoft.ApiManagement/stable/2018-01-01/apimsubscriptions.json
- Microsoft.ApiManagement/stable/2018-01-01/apimtagresources.json
- Microsoft.ApiManagement/stable/2018-01-01/apimtags.json
- Microsoft.ApiManagement/stable/2018-01-01/apimtenant.json
- Microsoft.ApiManagement/stable/2018-01-01/apimusers.json
- Microsoft.ApiManagement/stable/2018-01-01/apimversionsets.json
```

## Suppression

``` yaml
directive:
  - suppress: R3016
    reason: existing properties, can't be changed without breaking API.
    #where:
    #  - $.definitions.ApiManagementServiceUploadCertificateParameters.properties.certificate_password
    #  - $.definitions.QuotaCounterContract.properties.Value

```

### Tag: package-2017-03

These settings apply only when `--tag=package-2017-03` is specified on the command line.

``` yaml $(tag) == 'package-2017-03'
input-file:
- Microsoft.ApiManagement/stable/2017-03-01/apimanagement.json
- Microsoft.ApiManagement/stable/2017-03-01/apimapis.json
- Microsoft.ApiManagement/stable/2017-03-01/apimauthorizationservers.json
- Microsoft.ApiManagement/stable/2017-03-01/apimbackends.json
- Microsoft.ApiManagement/stable/2017-03-01/apimcertificates.json
- Microsoft.ApiManagement/stable/2017-03-01/apimdeployment.json
- Microsoft.ApiManagement/stable/2017-03-01/apimdiagnostics.json
- Microsoft.ApiManagement/stable/2017-03-01/apimemailtemplate.json
- Microsoft.ApiManagement/stable/2017-03-01/apimgroups.json
- Microsoft.ApiManagement/stable/2017-03-01/apimidentityprovider.json
- Microsoft.ApiManagement/stable/2017-03-01/apimloggers.json
- Microsoft.ApiManagement/stable/2017-03-01/apimnotifications.json
- Microsoft.ApiManagement/stable/2017-03-01/apimnetworkstatus.json
- Microsoft.ApiManagement/stable/2017-03-01/apimopenidconnectproviders.json
- Microsoft.ApiManagement/stable/2017-03-01/apimportalsettings.json
- Microsoft.ApiManagement/stable/2017-03-01/apimproducts.json
- Microsoft.ApiManagement/stable/2017-03-01/apimproperties.json
- Microsoft.ApiManagement/stable/2017-03-01/apimquotas.json
- Microsoft.ApiManagement/stable/2017-03-01/apimreports.json
- Microsoft.ApiManagement/stable/2017-03-01/apimsubscriptions.json
- Microsoft.ApiManagement/stable/2017-03-01/apimtagresources.json
- Microsoft.ApiManagement/stable/2017-03-01/apimtags.json
- Microsoft.ApiManagement/stable/2017-03-01/apimtenant.json
- Microsoft.ApiManagement/stable/2017-03-01/apimusers.json
- Microsoft.ApiManagement/stable/2017-03-01/apimversionsets.json
```

### Tag: package-2016-10

These settings apply only when `--tag=package-2016-10` is specified on the command line.

``` yaml $(tag) == 'package-2016-10'
input-file:
- Microsoft.ApiManagement/stable/2016-10-10/apimanagement.json
- Microsoft.ApiManagement/stable/2016-10-10/apimapis.json
- Microsoft.ApiManagement/stable/2016-10-10/apimauthorizationservers.json
- Microsoft.ApiManagement/stable/2016-10-10/apimbackends.json
- Microsoft.ApiManagement/stable/2016-10-10/apimcertificates.json
- Microsoft.ApiManagement/stable/2016-10-10/apimdeployment.json
- Microsoft.ApiManagement/stable/2016-10-10/apimgroups.json
- Microsoft.ApiManagement/stable/2016-10-10/apimidentityprovider.json
- Microsoft.ApiManagement/stable/2016-10-10/apimloggers.json
- Microsoft.ApiManagement/stable/2016-10-10/apimnetworkstatus.json
- Microsoft.ApiManagement/stable/2016-10-10/apimopenidconnectproviders.json
- Microsoft.ApiManagement/stable/2016-10-10/apimproducts.json
- Microsoft.ApiManagement/stable/2016-10-10/apimproperties.json
- Microsoft.ApiManagement/stable/2016-10-10/apimquotas.json
- Microsoft.ApiManagement/stable/2016-10-10/apimreports.json
- Microsoft.ApiManagement/stable/2016-10-10/apimsubscriptions.json
- Microsoft.ApiManagement/stable/2016-10-10/apimtenant.json
- Microsoft.ApiManagement/stable/2016-10-10/apimusers.json
```

### Tag: package-2016-07

These settings apply only when `--tag=package-2016-07` is specified on the command line.

``` yaml $(tag) == 'package-2016-07'
input-file:
- Microsoft.ApiManagement/stable/2016-07-07/apimanagement.json
- Microsoft.ApiManagement/stable/2016-07-07/apimdeployment.json
```

---

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-net
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-python
  - repo: azure-sdk-for-js
  - repo: azure-sdk-for-node
    autorest_options:
      use: "@microsoft.azure/autorest.python@~3.0"
  - repo: azure-sdk-for-ruby
    after_scripts:
      - bundle install && rake arm:regen_all_profiles['azure_mgmt_api_management']
  - repo: azure-resource-manager-schemas
  - repo: azure-powershell
```

## Python

See configuration in [readme.python.md](./readme.python.md)

## Go

See configuration in [readme.go.md](./readme.go.md)

## Java

See configuration in [readme.java.md](./readme.java.md)

## Suppression

``` yaml
directive:
  - suppress: R4009
    from: apimapis.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimapiversionsets.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimauthorizationservers.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimbackends.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimbackends.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimcaches.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimcertificates.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimdeployment.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimsubscriptions.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimusers.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimproducts.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimnamedvalues.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimgateways.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimgroups.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimcontenttypes.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimdeletedservices.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimdiagnostics.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimemailtemplates.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimidentityprovider.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimissues.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimloggers.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimopenidconnectproviders.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimpolicies.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimportalrevisions.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimschema.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimsettings.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimtags.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimtenant.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4009
    from: apimnotifications.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: R4037
    from: definitions.json
    reason: We want customers to be able to supply any valid JSON token, object or otherwise    
  - suppress: R4009
    from: apimprivatelink.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.  
  - suppress: R4009
    from: apimprivatelink.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.  
  - suppress: R4009
    from: apimportalsettings.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.  
  - suppress: R4009
    from: apimportalconfigs.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.  
  - suppress: R4009
    from: apimpolicyfragments.json
    reason: Warning raised to error while PR was being reviewed. SystemData will implement in next preview version.
  - suppress: LroErrorContent
    from: apimapis.json
    reason: Error Schema not referencing Common Schema V2. Will fix in the future. 
  - suppress: LroErrorContent
    from: apimusers.json
    reason: Error Schema not referencing Common Schema V2. Will fix in the future. 
  - suppress: LroErrorContent
    from: apimpolicyrestrictionsvalidation.json
    reason: Error Schema not referencing Common Schema V2. Will fix in the future. 
suppressions:
  - code: PropertiesTypeObjectNoDefinition
    from: definitions.json
    reason: Invalid error
  - code: PutRequestResponseSchemeArm
    from: apimworkspacecertificates.json
    where: $.paths["/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/workspaces/{workspaceId}/certificates/{certificateId}"].put
    reason: Certificate is a secret and it should not be available through get request
  - code: GetCollectionOnlyHasValueAndNextLink
    from: apimworkspacecertificates.json
    where: $.paths["/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/workspaces/{workspaceId}/certificates].get.responses["200"].schema.properties
    reason: Our object contain count property as a sibling to nextLink and value and it used for proxy resource collection GETs.
  - code: GetCollectionOnlyHasValueAndNextLink
    from: apimworkspacebackends.json
    where: $.paths["/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/workspaces/{workspaceId}/backends"].get.responses["200"].schema.properties
    reason: Our object contain count property as a sibling to nextLink and value and it used for proxy resource collection GETs.
  - code: GetCollectionOnlyHasValueAndNextLink
    from: apimworkspacediagnostics.json
    where: 
      - $.paths["/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/workspaces/{workspaceId}/diagnostics"].get.responses["200"].schema.properties
      - $.paths["/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/workspaces/{workspaceId}/apis/{apiId}/diagnostics"].get.responses.["200"].schema.properties
    reason: Our object contain count property as a sibling to nextLink and value and it used for proxy resource collection GETs.
  - code: GetCollectionOnlyHasValueAndNextLink
    from: apimworkspaceloggers.json
    where: $.paths["/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/workspaces/{workspaceId}/loggers"].get.responses["200"].schema.properties
    reason: Our object contain count property as a sibling to nextLink and value and it used for proxy resource collection GETs.
  - code: PatchBodyParametersSchema
    from: apimworkspacebackends.json
    reasons: This are the object fields which when updated require some data to be present.

