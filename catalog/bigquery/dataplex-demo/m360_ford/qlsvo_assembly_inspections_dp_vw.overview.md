# qlsvo_assembly_inspections_dp_vw Overview

The `qlsvo_assembly_inspections_dp_vw` is a BigQuery table within the `dataplex-demo.m360_ford` dataset, categorized under Vehicle Assembly. This view likely provides detailed information pertaining to inspections conducted during the vehicle assembly process.

## Schema

The table `qlsvo_assembly_inspections_dp_vw` contains the following columns:

*   **assembly_inspections_dp_id** (STRING): A unique identifier for a specific assembly inspection record.
*   **unit_id** (STRING): An identifier for the individual unit undergoing inspection.
*   **vin** (STRING): The Vehicle Identification Number for the unit.
*   **vin__msk** (STRING): A masked version of the Vehicle Identification Number, likely for privacy or security purposes.
*   **physical_vin** (STRING): The physical Vehicle Identification Number.
*   **plant** (STRING): The identifier of the manufacturing plant where the inspection occurred.
*   **plant_code** (STRING): The code associated with the manufacturing plant.
*   **model_year** (STRING): The model year of the vehicle being inspected.
*   **unit_concern_id** (STRING): An identifier for any specific concern or issue related to the unit.
*   **created_on** (STRING): The timestamp indicating when the inspection record was created.
*   **modified_on** (STRING): The timestamp indicating when the inspection record was last modified.
*   **unit_collection_pt_timestamp_utc** (STRING): The timestamp in UTC when data for the unit was collected at a specific point.
*   **unit_collection_pt_timestamp_local** (STRING): The timestamp in local time when data for the unit was collected at a specific point.
*   **plant_name** (STRING): The name of the manufacturing plant.
*   **last_name** (STRING): The last name of an individual associated with the inspection, possibly the inspector.
*   **first_name** (STRING): The first name of an individual associated with the inspection, possibly the inspector.
*   **inspection_purpose_name** (STRING): The descriptive name of the purpose of the inspection.
*   **product_line_group_name** (STRING): The name of the product line group to which the vehicle belongs.

## Source References

*   BigQuery Table: `dataplex-demo.m360_ford.qlsvo_assembly_inspections_dp_vw`
