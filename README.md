# SAP ABAP Cloud Leave Management System (Fiori Elements)

## 🔍 Overview

This PoC demonstrates a Leave Management System using:
- ABAP Cloud (Steampunk) with Eclipse ADT
- Custom table + CDS View
- Fiori Elements List Report UI via OData V2

## 📁 Components

- `zleave_data`: Custom transparent table
- `zcds_leave_view`: CDS View with UI annotations
- `zsd_leave`: Service Definition exposing the CDS
- `zsb_leave`: Service Binding (OData V2)
- `zcl_leave_test_data`: ABAP class to insert sample data

## 🧪 Test Data

Run the class `ZCL_LEAVE_TEST_DATA` in Eclipse to insert test rows.

## 🚀 Fiori App

After publishing the service binding:
- Right-click → Preview → App opens in browser
- Filter or click "Go" to view records

## 🛠 Future Enhancements

- Add Behavior Definitions for Create/Edit support
- Use AMDP for calculated fields 




