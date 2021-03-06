﻿# Delete features (feature service)

Delete features from an online feature service.

![Screenshot](DeleteFeatures.jpg)

## How to use the sample

Select a feature, then use the button to delete it.

## How it works

To delete a `Feature` from a `ServiceFeatureTable`:

1. Create a service feature table from a URL.
2. Create a `FeatureLayer` from the service feature table.
3. Select features from the feature layer via `FeatureLayer.SelectFeatures()`.
4. Remove the selected features from the ServiceFeatureTable using `ServiceFeatureTable.DeleteFeatureAsync()`.
5. Update the table on the server using `ServiceFeatureTable.ApplyEditsAsync()`.

## Relevant API

* Map
* Feature
* FeatureLayer
* MapView
* ServiceFeatureTable

## Tags

Service, table, feature, deletion, online