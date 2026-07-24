# qlscm_quarantine_dp_vw Overview

The `qlscm_quarantine_dp_vw` is a BigQuery table, part of the `dataplex-demo.m360_ford` dataset, categorized under Supply Chain Management. It likely captures data points related to quarantined items or units within a supply chain or manufacturing process.

## Schema

The table comprises the following columns:

*   **`quarantine_dp_id`** (STRING): An identifier for a specific quarantine data point.
*   **`unit_id`** (STRING): An identifier for a unit.
*   **`vin`** (STRING): The Vehicle Identification Number.
*   **`vin__msk`** (STRING): A masked version of the Vehicle Identification Number.
*   **`plant`** (STRING): The manufacturing plant associated with the unit or quarantine event.
*   **`operation_id`** (STRING): An identifier for an operation.
*   **`component_id`** (STRING): An identifier for a component.
*   **`unit_status_code`** (STRING): A code indicating the status of the unit.
*   **`created_on`** (STRING): The date and time when the record was created.
*   **`modified_on`** (STRING): The date and time when the record was last modified.
*   **`mfg_process_sakey`** (STRING): A surrogate key for the manufacturing process.
*   **`quar_sakey`** (STRING): A surrogate key specifically for quarantine.
*   **`stn_group_sakey`** (STRING): A surrogate key for the station group.
*   **`trace_comp_sakey`** (STRING): A surrogate key for traceability components.
*   **`update_dts_utc`** (STRING): The update timestamp in Coordinated Universal Time (UTC).
*   **`update_dts_local`** (STRING): The update timestamp in local time.
*   **`status_desc`** (STRING): A description of the status.
*   **`unit_type_desc`** (STRING): A description of the unit type.
