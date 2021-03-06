# Get-VCFNetworkIPPool

### Synopsis
Get a Network of a Network Pool

### Syntax
```
Get-VCFNetworkIPPool -id <string>
```

### Description
The Get-VCFNetworkIPPool cmdlet connects to the specified SDDC Manager and retrieves a list of the networks configured for the provided network pool.


### Examples
#### Example 1
```
Get-VCFNetworkIPPool -id 917bcf8f-93e8-4b84-9627-471899c05f52
```
This example shows how to get a list of all networks associated to the network pool based on the id provided

#### Example 2
```
Get-VCFNetworkIPPool -id 917bcf8f-93e8-4b84-9627-471899c05f52 -networkid c2197368-5b7c-4003-80e5-ff9d3caef795 	
```
This example shows how to get a list of details for a specific network associated to the network pool using ids

### Parameters

#### -id
- ID of target Network Pool

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
```

#### -networkid
- ID of target IP Pool

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: False
Position: Named
Default value: None
```

### Notes

### Related Links
