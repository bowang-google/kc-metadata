# qlscm_non_compliance_dp_vw Overview

The `qlscm_non_compliance_dp_vw` is a BigQuery table within the `dataplex-demo.m360_ford` dataset, categorized under Supply Chain Management. It serves as a view providing data points related to non-compliance incidents.

## Schema

The table comprises the following columns, detailing various aspects of non-compliance events:

*   **non_compliance_dp_id**: A unique identifier for a specific non-compliance data point.
*   **unit_id**: An identifier for the unit associated with the non-compliance.
*   **vin**: The Vehicle Identification Number of the affected unit.
*   **vin__msk**: A masked version of the Vehicle Identification Number, likely for privacy or restricted access.
*   **plant**: The manufacturing plant where the non-compliance occurred or was recorded.
*   **created_on**: The date and time when the non-compliance record was initially created.
*   **modified_on**: The date and time when the non-compliance record was last modified.
*   **process_dts_utc**: The processing date and time in Coordinated Universal Time (UTC).
*   **process_dts_local**: The processing date and time in the local timezone.
*   **root_cause_desc**: A descriptive text explaining the root cause of the non-compliance.
*   **station_desc**: A description of the station or location within the plant where the non-compliance was identified.
*   **repair_code_desc**: A description of the repair code associated with addressing the non-compliance.
*   **comp_type_desc**: A description of the component type involved in the non-compliance.
*   **nc_code_desc**: A descriptive text for the non-compliance code itself.
*   **nc_location_code_desc**: A descriptive text for the specific location code where the non-compliance was found.
*   **operation_desc**: A description of the operation during which the non-compliance occurred.
*   **root_cause_name**: The name given to the root cause of the non-compliance.
*   **repair_code_name**: The name of the repair code used to address the non-compliance.

## Source References

This overview is based on the table's schema and metadata.
