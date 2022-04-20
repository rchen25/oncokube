# Digital Slide Arhive

## API documentation

https://api.digitalslidearchive.org/api/v1


## API GET request example

```
$ curl -X GET --header 'Accept: application/json' \ 
        'https://api.digitalslidearchive.org/api/v1/tcga/case/label/TCGA-02-0006'
```

returns 

```
{"_id": "5b9fe011e62914002e970324", "access": {"groups": [], "users": [{"flags": [], "id": "5b9ef8cbe62914002e3e7247", "level": 2}]}, "baseParentId": "5b9ef8e3e62914002e454c39", "baseParentType": "collection", "created": "2018-09-17T17:10:41.817000+00:00", "creatorId": "5b9ef8cbe62914002e3e7247", "description": "", "lowerName": "tcga-02-0006", "meta": {"cohort": "gbm"}, "name": "TCGA-02-0006", "parentCollection": "folder", "parentId": "5b9f00e9e62914002e94cef0", "public": true, "size": 0, "tcga": {"caseId": "5b9fe011e62914002e970324", "cohort": "gbm", "label": "TCGA-02-0006", "meta": {"nationwidechildrens-org_biospecimen_aliquot_gbm": {"bcr_aliquot_barcode": "TCGA-02-0006-10A-01W-0190-09", "bcr_aliquot_uuid": "c0b78069-fec6-4f04-9d80-44ba0add74e4", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_sample_barcode": "TCGA-02-0006-10A", "center_id": "09", "concentration": "0.50", "date_of_shipment": "2007-04-17", "is_derived_from_ffpe": "NO", "plate_column": "6", "plate_id": "0190", "plate_row": "C", "quantity": "200.00", "source_center": "22", "volume": "400.00"}, "nationwidechildrens-org_biospecimen_analyte_gbm": {"amount": "0.00", "analyte_type": "Repli-G (Qiagen) DNA", "analyte_type_id": "W", "bcr_analyte_barcode": "TCGA-02-0006-10A-01W", "bcr_analyte_uuid": "ca4d7c4a-5fce-4071-b0c8-7114c7f06024", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_sample_barcode": "TCGA-02-0006-10A", "concentration": "0.50", "gel_image_file": "https://sharedoc.nchri.org/tcga-bcr/default.aspx", "is_derived_from_ffpe": "NO", "normal_tumor_genotype_match": "YES", "pcr_amplification_successful": "NO", "spectrophotometer_method": "UV Spec"}, "nationwidechildrens-org_biospecimen_cqcf_gbm": {"bcr_patient_barcode": "TCGA-02-0006", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb"}, "nationwidechildrens-org_biospecimen_diagnostic_slides_gbm": {"bcr_patient_barcode": "TCGA-02-0006", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_sample_barcode": "TCGA-02-0006-01B", "ffpe_slide_uuid": "f55eb13f-5816-4490-b2aa-675b20676e5c"}, "nationwidechildrens-org_biospecimen_portion_gbm": {"bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_portion_barcode": "TCGA-02-0006-10A-01", "bcr_portion_uuid": "1ec45792-99a0-4f66-92c0-b40b9cacdcd6", "bcr_sample_barcode": "TCGA-02-0006-10A", "date_of_creation": "2011-07-14", "is_ffpe": "NO", "portion_number": "01"}, "nationwidechildrens-org_biospecimen_protocol_gbm": {"bcr_analyte_barcode": "TCGA-02-0006-10A-01W", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_sample_barcode": "TCGA-02-0006-10A", "experimental_protocol_type": "Repli-G"}, "nationwidechildrens-org_biospecimen_sample_gbm": {"bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_sample_barcode": "TCGA-02-0006-10A", "bcr_sample_uuid": "16b24b92-25e9-464c-bb6a-469e1f045f56", "is_ffpe": "NO", "sample_type": "Blood Derived Normal", "sample_type_id": "10", "vial_number": "A"}, "nationwidechildrens-org_biospecimen_slide_gbm": {"bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_sample_barcode": "TCGA-02-0006-01B", "bcr_slide_barcode": "TCGA-02-0006-01B-01-TS2", "bcr_slide_uuid": "15b581bb-b760-46b4-b8ae-79c1fcd17d67", "image_file_name": "TCGA-02-0006-01B-01-TS2.svs", "is_derived_from_ffpe": "NO", "percent_necrosis": "5", "percent_normal_cells": "0", "percent_stromal_cells": "0", "percent_tumor_cells": "95", "percent_tumor_nuclei": "100", "section_location": "TOP"}, "nationwidechildrens-org_clinical_drug_gbm": {"bcr_drug_barcode": "TCGA-02-0006-D22188", "bcr_drug_uuid": "92099a94-6caa-4884-816f-3debbd48ffea", "bcr_patient_barcode": "TCGA-02-0006", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "form_completion_date": "2010-1-12", "pharmaceutical_therapy_drug_name": "Temozolomide", "pharmaceutical_therapy_type": "Chemotherapy", "route_of_administration": "Oral", "therapy_regimen": "RECURRENCE", "therapy_regimen_other": "[Not Applicable]"}, "nationwidechildrens-org_clinical_follow_up_v1-0_gbm": {"bcr_followup_barcode": "TCGA-02-0006-F22185", "bcr_followup_uuid": "679559e4-a79a-42d0-80ff-e7c637f5cc28", "bcr_patient_barcode": "TCGA-02-0006", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "death_days_to": "558", "form_completion_date": "2008-12-17", "karnofsky_score": "80", "last_contact_days_to": "558", "pharmaceutical_tx_adjuvant": "YES", "radiation_treatment_adjuvant": "YES", "tumor_status": "WITH TUMOR", "vital_status": "Dead"}, "nationwidechildrens-org_clinical_follow_up_v1-0_nte_gbm": {"bcr_followup_barcode": "TCGA-02-0006-F22185", "bcr_patient_barcode": "TCGA-02-0006", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "new_neoplasm_event_type": "Locoregional Disease", "new_tumor_event_additional_surgery_procedure": "YES", "new_tumor_event_pharmaceutical_tx": "YES", "new_tumor_event_radiation_tx": "NO"}, "nationwidechildrens-org_clinical_patient_gbm": {"age_at_initial_pathologic_diagnosis": "56", "bcr_patient_barcode": "TCGA-02-0006", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "birth_days_to": "-20516", "days_to_initial_pathologic_diagnosis": "0", "death_days_to": "558", "ethnicity": "NOT HISPANIC OR LATINO", "form_completion_date": "2008-12-17", "gender": "FEMALE", "histological_type": "Untreated primary (de novo) GBM", "history_lgg_dx_of_brain_tissue": "NO", "history_neoadjuvant_treatment": "No", "icd_10": "C71.9", "icd_o_3_histology": "9440/3", "icd_o_3_site": "C71.9", "informed_consent_verified": "YES", "initial_pathologic_dx_year": "2002", "karnofsky_score": "80", "last_contact_days_to": "558", "method_initial_path_dx": "Tumor resection", "method_initial_path_dx_other": "[Not Applicable]", "patient_id": "0006", "race": "WHITE", "tissue_source_site": "02", "tumor_status": "WITH TUMOR", "tumor_tissue_site": "Brain", "vital_status": "Dead"}, "nationwidechildrens-org_clinical_radiation_gbm": {"bcr_patient_barcode": "TCGA-02-0006", "bcr_patient_uuid": "98714d95-b62e-4f34-9cd1-91542da463eb", "bcr_radiation_barcode": "TCGA-02-0006-R22189", "bcr_radiation_uuid": "3bcc9ca0-54ce-4931-90d6-12c5633d451f", "form_completion_date": "2009-3-30", "radiation_adjuvant_fractions_total": "30", "radiation_adjuvant_units": "cGy", "radiation_therapy_ended_days_to": "67", "radiation_therapy_site": "Primary Tumor Field", "radiation_therapy_started_days_to": "21", "radiation_therapy_type": "EXTERNAL BEAM", "radiation_total_dose": "6000", "radiation_type_other": "[Not Applicable]", "therapy_regimen": "ADJUVANT"}}, "type": "case", "uuid": "98714d95-b62e-4f34-9cd1-91542da463eb"}, "updated": "2019-10-17T06:00:27.250000+00:00"}

```