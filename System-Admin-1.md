# System Admin 1

## Create Company
- Go to Configuration > Organization > Companie
- Click (+) to add Company
- Fill in the following fields:
    - Header Section
        * Company ID
        * Company Name
    - Company Details
        * Country
        * Weight UOM
        * Volume UOM
- Save

## Create Branches
- Go to Configuration > Organization > Branches
- Click (+) to add Branch
- Fill in the following fields:
    - Header Section
        * Branch ID
        * Branch Name
        * Company
    - Company Details
        * Country
- Save

## Create Numbering Sequence
- Go to Configuration > Common Setting > Numbering Sequence
- Click (+) to add Numbering Sequence.
- Fill in the following fields:
    - Header Section
        * Numbering ID
        * Description
        * New Number Symbol (<NEW>)
    - Detail Section
        * Start Number
        * End Number
        * Start Date
        * Last Number
        * Warning Number

## Create Attributes
- Go to Configuration > Common Setting > Attribute
- Click (+) to add Attribute.
- Fill in the following fields:
    - Header Section
        * Attribute ID
        * Description
        * Select control type - text, combo, multi select combo and checkbox
- Save

## Create Snapshot
- Go to System Management > System Maintenance > Tenant
- Select the company that need to copy.
- Click Create Snapshot
- Fill in the following fields:
    - Description
    - Choose ‘Export Mode’
    - Check ‘Prepare for Export’

