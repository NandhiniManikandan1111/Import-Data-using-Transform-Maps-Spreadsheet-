# Phase 3 - Project Design

## System Flow

Spreadsheet
     ↓
Import Set
     ↓
Import Set Table
     ↓
Transform Map
     ↓
Field Mapping
     ↓
Target ServiceNow Table
     ↓
Imported Records

## Source Fields

| Source Field | Description |
|---|---|
| Employee ID | Unique employee identifier |
| Employee Name | Name of employee |
| Email | Employee email |
| Department | Employee department |
| Location | Employee location |

## Target Fields

The source fields are mapped to corresponding fields in the ServiceNow target table.

## Design Objective

The design ensures that spreadsheet data is correctly transformed and stored in the target ServiceNow table.
