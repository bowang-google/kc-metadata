# qlsvo_assembly_inspections_dp_vw Overview

This entry describes the `qlsvo_assembly_inspections_dp_vw` BigQuery table, which is part of the `dataplex-demo.m360_ford` dataset. Its metadata is defined and managed using a "metadata as code" strategy within a GitHub repository.

## Key Features

The definition for `qlsvo_assembly_inspections_dp_vw` is sourced from the `bowang-google/kc-metadata` GitHub repository, which implements a metadata as code strategy for a Dataplex instance. This repository serves as a source-code component (`bowang-google/kc-metadata`) that defines metadata for Google Cloud data assets, including BigQuery datasets and tables. The `catalog` directory within this repository contains a hierarchical structure of YAML files, where `qlsvo_assembly_inspections_dp_vw` is defined as a table within the `m360_ford` dataset.

## Schema

The `qlsvo_assembly_inspections_dp_vw` table contains the following columns:

*   **assembly_inspections_dp_id** (STRING): A unique identifier for assembly inspections.
*   **unit_id** (STRING): An identifier for the manufacturing unit.
*   **vin** (STRING): The Vehicle Identification Number.
*   **vin__msk** (STRING): A masked version of the Vehicle Identification Number.
*   **physical_vin** (STRING): The physical Vehicle Identification Number.
*   **plant** (STRING): The code for the manufacturing plant.
*   **plant_code** (STRING): The code for the manufacturing plant.
*   **model_year** (STRING): The model year of the vehicle.
*   **unit_concern_id** (STRING): An identifier for a concern related to the unit.
*   **created_on** (STRING): The timestamp indicating when the record was created.
*   **modified_on** (STRING): The timestamp indicating when the record was last modified.
*   **unit_collection_pt_timestamp_utc** (STRING): The timestamp in UTC when the unit was collected at a specific point.
*   **unit_collection_pt_timestamp_local** (STRING): The timestamp in local time when the unit was collected at a specific point.
*   **plant_name** (STRING): The name of the manufacturing plant.
*   **last_name** (STRING): The last name associated with the inspection, potentially an inspector.
*   **first_name** (STRING): The first name associated with the inspection, potentially an inspector.
*   **inspection_purpose_name** (STRING): The name describing the purpose of the inspection.
*   **product_line_group_name** (STRING): The name of the product line group.

## Source References

*   [Dataplex Metadata Catalog](https://github.com/bowang-google/kc-metadata)
