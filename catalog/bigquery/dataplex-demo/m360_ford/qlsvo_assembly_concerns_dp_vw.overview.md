# qlsvo_assembly_concerns_dp_vw Overview

The `qlsvo_assembly_concerns_dp_vw` is a BigQuery table, specifically a view, located in the `dataplex-demo.m360_ford` dataset. It is designed to capture data related to assembly concerns, identified by various unit and concern identifiers, along with timestamps and causal part descriptions.

## Metadata Management

The metadata for this table is managed using a "metadata as code" strategy within the `bowang-google/kc-metadata` GitHub repository. This repository defines metadata for Google Cloud data assets, including BigQuery datasets and tables, using YAML files. The table's definition is part of a hierarchical structure within the `catalog` directory, under `catalog/bigquery/dataplex-demo/m360_ford/`, where YAML files specify properties like resource name, display name, location, and type for tables within the `m360_ford` dataset.

## Schema

The `qlsvo_assembly_concerns_dp_vw` table contains the following columns:

*   `unit_concern_id`: STRING [NULLABLE]
*   `unit_id`: STRING [NULLABLE]
*   `vin`: STRING [NULLABLE]
*   `vin__msk`: STRING [NULLABLE]
*   `physical_vin`: STRING [NULLABLE]
*   `plant`: STRING [NULLABLE]
*   `plant_code`: STRING [NULLABLE]
*   `model_year`: STRING [NULLABLE]
*   `concern_id`: STRING [NULLABLE]
*   `unit_concern_state`: STRING [NULLABLE]
*   `created_on`: STRING [NULLABLE]
*   `modified_on`: STRING [NULLABLE]
*   `assembly_concerns_dp_id`: STRING [NULLABLE]
*   `produced_date_utc`: STRING [NULLABLE]
*   `unit_collection_pt_timestamp_utc`: STRING [NULLABLE]
*   `produced_date_local`: STRING [NULLABLE]
*   `unit_collection_pt_timestamp_local`: STRING [NULLABLE]
*   `ii_causal_part_desc`: STRING [NULLABLE]

## Source References

*   [Dataplex Metadata Catalog](https://github.com/bowang-google/kc-metadata)
