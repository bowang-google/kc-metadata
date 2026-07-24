# qlsvo_assembly_repairs_dp_vw Overview

The `qlsvo_assembly_repairs_dp_vw` is a BigQuery table located at `dataplex-demo.m360_ford.qlsvo_assembly_repairs_dp_vw`. Its metadata, along with other Google Cloud data assets, is managed through a "metadata as code" strategy implemented in the `bowang-google/kc-metadata` GitHub repository. This repository defines BigQuery datasets and tables using a hierarchical structure of YAML files.

## Source of Metadata

The definition for this BigQuery table, including its properties, is part of a "metadata as code" strategy. This approach uses the `bowang-google/kc-metadata` GitHub repository to store and manage metadata for a Dataplex instance. Specifically, the metadata for tables like `qlsvo_assembly_repairs_dp_vw` is defined in YAML files found within the `catalog` directory of this GitHub repository. This ensures that the metadata is version-controlled and can be managed alongside other source code.

## Schema

The `qlsvo_assembly_repairs_dp_vw` table contains the following columns, providing details on assembly repairs:

*   **assembly_repairs_dp_id**: A unique identifier for the assembly repair data point.
*   **unit_id**: Identifier for the specific unit involved in the repair.
*   **vin**: The Vehicle Identification Number.
*   **vin__msk**: A masked version of the Vehicle Identification Number.
*   **physical_vin**: The physical Vehicle Identification Number.
*   **plant**: The manufacturing plant associated with the unit.
*   **plant_code**: The code for the manufacturing plant.
*   **concern_id**: An identifier for the concern leading to the repair.
*   **unit_concern_id**: Identifier for the specific concern related to the unit.
*   **unit_concern_state**: The current state of the unit's concern.
*   **repair_state**: The current state of the repair.
*   **created_on**: Timestamp indicating when the record was created.
*   **modified_on**: Timestamp indicating when the record was last modified.
*   **unit_collection_pt_timestamp_utc**: The timestamp (UTC) when the unit was collected at a certain point.
*   **unit_repair_timestamp_utc**: The timestamp (UTC) when the unit repair occurred.
*   **unit_collection_pt_timestamp_local**: The timestamp (local time) when the unit was collected at a certain point.
*   **unit_repair_timestamp_local**: The timestamp (local time) when the unit repair occurred.
*   **plant_unit_location_name**: The name of the unit's location within the plant.

## Source References

*   [Dataplex Metadata Catalog](https://github.com/bowang-google/kc-metadata)
