# qlscm_quarantine_dp_vw Overview

The `qlscm_quarantine_dp_vw` entry represents a BigQuery table within the `dataplex-demo.m360_ford` dataset, falling under the QLSCM Supply Chain Data category. Its metadata is managed through a "metadata as code" strategy, defined in a GitHub repository.

## Metadata Management

This table's metadata is part of a "metadata as code" implementation for a Dataplex instance, residing in the `bowang-google/kc-metadata` GitHub repository. Within this repository, a hierarchical structure of YAML files in the `catalog` directory defines BigQuery datasets and tables. Specifically, the `qlscm_quarantine_dp_vw` table is identified as a key entity managed by this system, with its definition nested under the `m360_ford` dataset.

## Schema

The `qlscm_quarantine_dp_vw` table contains the following columns:

*   `quarantine_dp_id`: A string identifier for the quarantine data point.
*   `unit_id`: A string identifier for the unit.
*   `vin`: The Vehicle Identification Number as a string.
*   `vin__msk`: A masked version of the Vehicle Identification Number as a string.
*   `plant`: The plant where the unit was processed, as a string.
*   `operation_id`: A string identifier for the operation.
*   `component_id`: A string identifier for the component.
*   `unit_status_code`: A string representing the status code of the unit.
*   `created_on`: A string representing the creation timestamp.
*   `modified_on`: A string representing the modification timestamp.
*   `mfg_process_sakey`: A string representing the manufacturing process surrogate key.
*   `quar_sakey`: A string representing the quarantine surrogate key.
*   `stn_group_sakey`: A string representing the station group surrogate key.
*   `trace_comp_sakey`: A string representing the traceable component surrogate key.
*   `update_dts_utc`: A string representing the update timestamp in UTC.
*   `update_dts_local`: A string representing the update timestamp in local time.
*   `status_desc`: A string providing a description of the status.
*   `unit_type_desc`: A string providing a description of the unit type.

## Source References

*   [Dataplex Metadata Catalog](https://github.com/bowang-google/kc-metadata)
