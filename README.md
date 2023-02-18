https://docs.google.com/document/d/1VYOiuPpvihiwlP4_VV3P-JROYnS_P3OvNPtvOFABlrs/edit?usp=sharing


# [fsc_RadioButtonGroup CPE Component](https://app.tango.us/app/workflow/9b69d4d2-92d7-4726-971b-33dd37a16c4d?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)

__Creation Date:__ February 17, 2023  
__Created By:__ Andy Haas  
[View most recent version on Tango](https://app.tango.us/app/workflow/9b69d4d2-92d7-4726-971b-33dd37a16c4d?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)
***

### 1. [HTML Sample](https://app.tango.us/app/home)
<c-fsc\_flow-radio-group  
    name="showNewRecordAction"  
    label={inputValues.showNewRecordAction.label}  
    options={showNewRecordActionOptions}  
    value={inputValues.showNewRecordAction.flowValue}  
    type="button"  
    onvaluechange={handleValueChange}>  
\></c-fsc\_flow-radio-group>


### 2. JS Sample
// Show New Record Action Options  
get showNewRecordActionOptions  () {  
  return \[  
        {label: 'Show', value: '$GlobalConstant.True'},  
        {label: 'Hide', value: '$GlobalConstant.False'}  
    \];  
}


### 3. Event Handler Configuration
The value that is in outputted onvaluechange. 

event.detail.newValue;


### 4. End Result Look/Feel
![Step 4 screenshot](https://images.tango.us/workflows/9b69d4d2-92d7-4726-971b-33dd37a16c4d/steps/1be5d629-bf93-40ef-ae73-a57f5f82dcc4/18e55dba-1a7b-47dd-9aad-8472201faa94.png?crop=focalpoint&fit=crop&fp-x=0.5000&fp-y=0.5000&w=1200)


***
_[This Workflow was created with Tango](https://app.tango.us/app/workflow/9b69d4d2-92d7-4726-971b-33dd37a16c4d?utm_source=markdown&utm_medium=markdown&utm_campaign=workflow%20export%20links)_
