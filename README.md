# Analysing event logs from ERP systems for fraud examination> A process mining-based approach

This repository provides the pseudo-code for the SQL transformations for fraud examination with process mining.

## How to read the code?

The repository consists of 3 files: the Event\_Log\_Template, Create\_PurReq, and Change\_PO\_Items.

The Event\_Log\_Template defines the columns required to define the event log. SAP specific fields are commented as such. These columns need to be altered depending on the source ERP system used.

Create\_PurReq demonstrates mining events which involves creation of a new artefact within the process. It looks for new entries created in the designated table for the artefact.

Change\_PO\_Items demonstrates mining event which are conditional or tracking changes to existing artefacts through entries in change history.
