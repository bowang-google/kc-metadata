# qlscm_non_compliance_dp_vw Overview

The `qlscm_non_compliance_dp_vw` is a BigQuery table in the `dataplex-demo.m360_ford` dataset, categorized under QLSCM Supply Chain Data. Its metadata is defined and managed as code within a GitHub repository, specifically as part of a Dataplex "metadata as code" strategy. This table captures various details related to non-compliance in the supply chain.

## Key Columns

This table contains the following columns:

*   `non_compliance_dp_id`: A unique identifier for the non-compliance data point.
*   `unit_id`: An identifier for the unit involved.
*   `vin`: The Vehicle Identification Number.
*   `vin__msk`: A masked version of the Vehicle Identification Number.
*   `plant`: The manufacturing plant where the event occurred.
*   `created_on`: The date and time when the record was created.
*   `modified_on`: The date and time when the record was last modified.
*   `process_dts_utc`: The processing date and time in UTC.
*   `process_dts_local`: The processing date and time in local time.
*   `root_cause_desc`: A description of the root cause of the non-compliance.
*   `station_desc`: A description of the station where the non-compliance was identified.
*   `repair_code_desc`: A description of the repair code.
*   `comp_type_desc`: A description of the component type.
*   `nc_code_desc`: A description of the non-compliance code.
*   `nc_location_code_desc`: A description of the non-compliance location code.
*   `operation_desc`: A description of the operation involved.
*   `root_cause_name`: The name associated with the root cause.
*   `repair_code_name`: The name associated with the repair code.

## Lineage

The metadata for this BigQuery table is defined as part of a "metadata as code" strategy implemented in the `bowang-google/kc-metadata` GitHub repository. Specifically, its definition can be found within the `catalog/bigquery/dataplex-demo/m360_ford/qlscm_non_compliance_dp_vw.yaml` file, which is part of a hierarchical structure defining BigQuery datasets and tables for a Dataplex instance.

## Source References

*   [Dataplex Metadata Catalog](https://github.com/bowang-google/kc-metadata)
