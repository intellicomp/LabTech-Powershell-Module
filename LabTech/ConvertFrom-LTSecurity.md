# ConvertFrom-LTSecurity
## SYNOPSIS
This function decodes an encoded Base64 value
## SYNTAX
```powershell
ConvertFrom-LTSecurity [-InputString] <String[]> [-Key <String[]>] [-Force] [<CommonParameters>]
```
## DESCRIPTION
This function decodes the provided string using the specified or default key.
## PARAMETERS
### -InputString &lt;String[]&gt;
This is the string to be decoded.
```
Required                    true
Position                    2
Default value
Accept pipeline input       true (ByValue, ByPropertyName)
Accept wildcard characters  false
```
### -Key &lt;String[]&gt;
This is the key used for decoding. If not provided, default values will be tried.
```
Required                    false
Position                    named
Default value
Accept pipeline input       true (ByPropertyName)
Accept wildcard characters  false
```
### -Force &lt;SwitchParameter&gt;
This forces the function to try alternate key values if decoding fails using provided key.
```
Required                    false
Position                    named
Default value                True
Accept pipeline input       false
Accept wildcard characters  false
```
## NOTES
Version:        1.1

Author:         Darren White

Creation Date:  1/25/2018

Purpose/Change: Initial function development 
