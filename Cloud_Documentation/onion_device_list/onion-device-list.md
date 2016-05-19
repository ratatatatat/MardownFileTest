# **onion-device-list element**

The onion-device-list provides a filterable list of available devices to the user via the cloud. Devices can either be displayed in table or dropdown format. 
The selected device-id, device object( JSON with complete device info) and complete device array are available for usage in the parent element via element selectors. 
The flow chart below visually describes usage. 

## FlowChart 



## Usage 

### Device List Table Format

For a non-filtered device-list in a table format, include the following line in your parent element:

```
<onion-device-list></onion-device-list>
```

### Device List Dropdown Format

For a non-filtered device-list in a dropdown format, include the following line in your parent element:
```
<onion-device-list drop-down="true"></onion-device-list>
```

### Adding Device List Filters

Filters can be applied to both the dropdown and table device list formats, using the "online-only" and "can-manage" attributes. There are for 4 filter settings.

 
#### 1)No filter

Do not include the "online-only" and "can-manage" attribute inside the onion-device-list tag.

```
<onion-device-list></onion-device-list>
```

#### 2)Online-Only Filter
Include the "online-only="true"" attribute inside the onion-device-list tag.

```
<onion-device-list online-only="true"></onion-device-list>
```
#### 3)Can-Manage Filter
Include the "can-manage="true"" attribute inside the onion-device-list tag.

```
<onion-device-list can-manage="true"></onion-device-list>
```
#### 4)Can-Manage and Online-Only Filter
Include the "can-manage="true"" and "online-only="true"" attributes inside the onion-device-list tag.

```
<onion-device-list can-manage="true" online-only="true"></onion-device-list>
```