# qlsvo_assembly_concerns_dp_vw Overview

The `qlsvo_assembly_concerns_dp_vw` is a BigQuery table in the `dataplex-demo.m360_ford` dataset, categorized under Vehicle Assembly. This view provides detailed information about concerns identified during the assembly process of individual vehicle units.

## Schema

This table contains the following columns, detailing various aspects of vehicle assembly concerns:

*   **unit_concern_id**: A unique identifier for a specific concern associated with a particular unit.
*   **unit_id**: A unique identifier for the vehicle unit to which the concern relates.
*   **vin**: The Vehicle Identification Number of the unit.
*   **vin__msk**: The masked Vehicle Identification Number.
*   **physical_vin**: The physical Vehicle Identification Number, potentially distinct from other VIN representations.
*   **plant**: The manufacturing plant where the vehicle unit was assembled.
*   **plant_code**: The code identifying the manufacturing plant.
*   **model_year**: The model year of the vehicle unit.
*   **concern_id**: A general identifier for the type of concern.
*   **unit_concern_state**: The current status or state of the concern for the unit (e.g., open, closed).
*   **created_on**: The timestamp indicating when the unit concern record was initially created.
*   **modified_on**: The timestamp indicating when the unit concern record was last modified.
*   **assembly_concerns_dp_id**: An identifier specific to assembly concerns within the Data Platform.
*   **produced_date_utc**: The production date of the unit, recorded in Coordinated Universal Time (UTC).
*   **unit_collection_pt_timestamp_utc**: The timestamp for the unit's collection point, recorded in Coordinated Universal Time (UTC).
*   **produced_date_local**: The production date of the unit, recorded in local time.
*   **unit_collection_pt_timestamp_local**: The timestamp for the unit's collection point, recorded in local time.
*   **ii_causal_part_desc**: A description of the causal part associated with the identified concern.

## Source References

*   BigQuery table metadata for `dataplex-demo.m360_ford.qlsvo_assembly_concerns_dp_vw`
