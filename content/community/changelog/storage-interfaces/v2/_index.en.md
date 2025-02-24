---
title: v2
description: Overview of changes introduced in v2 of the Altinn.Platform.Storage.Interface package.
toc: true
weight: 100
---

## 2.5.10 Dependency on .NETStandard2.0

- The package was changed to depend on .NetStandard2.0 in place of .NetStandard2.1. This should ensure that applications based on .NET Framework 4.7 can use the package.

## 2.5.9 Expanded the eFormidlingContract with SecurityLevel

- eFormidlingContract model was given a new property holding security level information. [#5740](https://github.com/Altinn/altinn-studio/issues/5740)

## 2.5.8 Extended eFormidlingContract with additional parameters

- eFormidlingContract model was given three new properties to support eFormidling in apps. [#5740](https://github.com/Altinn/altinn-studio/issues/5740)

## 2.5.7 Extended eFormidlingContract with a new property: sendAfterTaskId

- eFormidlingContract model was given a new property to identify which task should trigger an eFormidling shipment. [#5740](https://github.com/Altinn/altinn-studio/issues/5740)

## 2.5.6 Adjustments around PresentationField and texts

- Fixes to how PresentationFields were annotated.
- New class PresentationTexts to hold a list of texts generated by presentation field rules on an instance.

## 2.5.5 Added PresentationFields to Application

- New class PresentationField to represent a data extraction rule.
- Instance model was given a new property called *presentationFields*. [#5638](https://github.com/Altinn/altinn-studio/issues/5638)

## 2.5.4 Fix the OpenAPI specification of ReadStatus

- ReadStatus was changed to be defined as a string. [#5637](https://github.com/Altinn/altinn-studio/issues/5637)

## 2.5.3 eFormidling support

- Added a new model to support integration with eFormidling.

## 2.5.2 Dependency on .NETStandard2.1

- The package was changed to depend on .NetStandard2.1 in place of .NETCoreApp3.1. 
- The dependency to the Microsoft.AspNetCore.Mvc.NewtonsoftJson package was removed and there is now instead a direct dependency to the Newtonsoft.Json package.

## 2.5.1 DataElement IsRead is true by default

- The value of IsRead is changed to have default value true.
