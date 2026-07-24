# qlsvo_assembly_repairs_dp_vw Overview

The `qlsvo_assembly_repairs_dp_vw` is a BigQuery table, specifically `dataplex-demo.m360_ford.qlsvo_assembly_repairs_dp_vw`, categorized under Vehicle Assembly. This table appears to store detailed information pertaining to repairs performed on vehicle assemblies.

## Schema

The table comprises the following columns, providing insights into vehicle assembly repairs:

*   **assembly_repairs_dp_id** (STRING): A unique identifier for a specific data point related to an assembly repair.
*   **unit_id** (STRING): An identifier for the vehicle assembly unit undergoing repair.
*   **vin** (STRING): The Vehicle Identification Number associated with the assembly.
*   **vin__msk** (STRING): A masked version of the Vehicle Identification Number, potentially used for privacy or aggregated reporting.
*   **physical_vin** (STRING): The physical Vehicle Identification Number of the assembly.
*   **plant** (STRING): The name of the manufacturing plant where the assembly or repair activity took place.
*   **plant_code** (STRING): The code identifying the manufacturing plant.
*   **concern_id** (STRING): An identifier for a particular concern or issue identified with the assembly.
*   **unit_concern_id** (STRING): A specific identifier for a concern associated with the unit.
*   **unit_concern_state** (STRING): The current state of the concern identified for the unit.
*   **repair_state** (STRING): The current state or status of the repair process for the assembly.
*   **created_on** (STRING): The timestamp indicating when the record was created.
*   **modified_on** (STRING): The timestamp indicating when the record was last modified.
*   **unit_collection_pt_timestamp_utc** (STRING): The timestamp, in Coordinated Universal Time (UTC), when the unit reached a specific collection point.
*   **unit_repair_timestamp_utc** (STRING): The timestamp, in Coordinated Universal Time (UTC), when the repair on the unit occurred.
*   **unit_collection_pt_timestamp_local** (STRING): The timestamp, in local time, when the unit reached a specific collection point.
*   **unit_repair_timestamp_local** (STRING): The timestamp, in local time, when the repair on the unit occurred.
*   **plant_unit_location_name** (STRING): The name of the specific location within the plant where the unit is situated.
