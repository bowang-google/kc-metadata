# qlscm_scrapped_dp_vw Overview

The `qlscm_scrapped_dp_vw` is a BigQuery table, part of the `dataplex-demo.m360_ford` dataset, falling under the Supply Chain Management category. It likely contains data pertaining to scrapped units or components within a supply chain or manufacturing context.

## Schema

The table `qlscm_scrapped_dp_vw` contains the following columns:

*   `scrapped_dp_id` (STRING): A unique identifier for a scrapped data point.
*   `unit_id` (STRING): An identifier for the specific unit involved.
*   `vin` (STRING): The Vehicle Identification Number of the unit.
*   `vin__msk` (STRING): A masked version of the Vehicle Identification Number, potentially used for privacy or security.
*   `plant` (STRING): The manufacturing plant where the event occurred.
*   `operation_id` (STRING): An identifier for the operation related to the scrapped item.
*   `created_on` (STRING): The date when the record was initially created.
*   `modified_on` (STRING): The date when the record was last modified.
*   `quar_sakey` (STRING): A surrogate key, possibly related to a quarantine or quality assurance aspect.
*   `mfg_process_sakey` (STRING): A surrogate key identifying the manufacturing process.
*   `stn_group_sakey` (STRING): A surrogate key for the station group associated with the event.
*   `trace_comp_sakey` (STRING): A surrogate key for a traced component.
*   `create_dts_utc` (STRING): The creation timestamp of the record in Coordinated Universal Time (UTC).
*   `scrap_dts_utc` (STRING): The timestamp when the item was scrapped, recorded in Coordinated Universal Time (UTC).
*   `update_dts_utc` (STRING): The timestamp of the last update to the record in Coordinated Universal Time (UTC).
*   `create_dts_local` (STRING): The creation timestamp of the record in local time.
*   `scrap_dts_local` (STRING): The timestamp when the item was scrapped, recorded in local time.
*   `update_dts_local` (STRING): The timestamp of the last update to the record in local time.

## Source References
* (None)
