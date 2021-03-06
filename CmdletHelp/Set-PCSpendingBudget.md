# Set-PCSpendingBudget

Updates the spending budget for the specified tenant.

## SYNTAX

```powershell
Set-PCSpendingBudget [[-TenantId] <String>] [-SpendingBudget] <String> [[-SaToken] <String>] [<CommonParameters>]
```

## DESCRIPTION

The Set-PCSpendingBudget cmdlet sets a spending budged for the specified tenant.

## PARAMETERS

### -TenantId &lt;String&gt;

Specifies the tenant for which to set the spending budget

```
Required?                    false
Position?                    1
Default value                $GlobalCustomerId
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -SpendingBudget &lt;String&gt;

Specifies the spending budget in the default currency for the partner.

```
Required?                    true
Position?                    2
Default value
Accept pipeline input?       false
Accept wildcard characters?  false
```

### -SaToken &lt;String&gt;

Specifies an authentication token with your Partner Center credentials.

```
Required?                    false
Position?                    3
Default value                $GlobalToken
Accept pipeline input?       false
Accept wildcard characters?  false
```

## INPUTS

## OUTPUTS

## NOTES

None

## EXAMPLES

### EXAMPLE 1

Sets the spending budget to 3000 USD.

```powershell
PS C:\>Set-PCSpendingBudget -TenantId 97037612-799c-4fa6-8c40-68be72c6b83c -SpendingBudget 3000
```
