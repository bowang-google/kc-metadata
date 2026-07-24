# qlscm_scrapped_dp_vw Overview

`qlscm_scrapped_dp_vw` is a BigQuery table located at `dataplex-demo.m360_ford.qlscm_scrapped_dp_vw`. It belongs to the QLSCM Supply Chain Data category.

## Schema

This table contains the following columns, all of which are nullable strings:

*   `scrapped_dp_id`: A unique identifier for a scrapped data point.
*   `unit_id`: Identifier for the unit.
*   `vin`: Vehicle Identification Number.
*   `vin__msk`: Masked Vehicle Identification Number, likely for privacy or security purposes.
*   `plant`: The plant associated with the record.
*   `operation_id`: Identifier for the operation.
*   `created_on`: Date of creation.
*   `modified_on`: Date of modification.
*   `quar_sakey`: Surrogate key for quarantine information.
*   `mfg_process_sakey`: Surrogate key for the manufacturing process.
*   `stn_group_sakey`: Surrogate key for the station group.
*   `trace_comp_sakey`: Surrogate key for trace components.
*   `create_dts_utc`: Creation timestamp in UTC.
*   `scrap_dts_utc`: Scrap timestamp in UTC.
*   `update_dts_utc`: Update timestamp in UTC.
*   `create_dts_local`: Creation timestamp in local time.
*   `scrap_dts_local`: Scrap timestamp in local time.
*   `update_dts_local`: Update timestamp in local time.

## Lineage and Metadata Management

The metadata for `qlscm_scrapped_dp_vw` is managed as code within the `bowang-google/kc-metadata` GitHub repository. This repository implements a "metadata as code" strategy for a Dataplex instance, where definitions for Google Cloud data assets, including BigQuery datasets and tables, are stored as YAML files.

Specifically, the `catalog.yaml` file at the root of the repository defines the overall scope of the metadata. BigQuery datasets and tables, such as `qlscm_scrapped_dp_vw`, are defined within a hierarchical structure of YAML files in the `catalog` directory. For example, the `m360_ford` dataset is defined in `catalog/bigquery/dataplex-demo/m360_ford.yaml`, and tables within that dataset, like `qlscm_scrapped_dp_vw`, have their definitions in corresponding YAML files within the `m360_ford` directory. Each YAML file contains properties such as the resource name, display name, location, and type for the data asset it describes.

## Source References

*   [bowang-google/kc-metadata: Dataplex Metadata Catalog](https://github.com/bowang-google/kc-metadata)
