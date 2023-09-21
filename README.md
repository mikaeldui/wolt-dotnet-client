# Wolt .NET Client (independent)
A .NET client for Wolt (DoorDash).

- [Documentation](https://developer.wolt.com/)

- [ ] Partner API
- [ ] Drive API

# Example

Of Partner API usage:

```c-sharp
using WoltPartnerClient woltPartnerClient = new("mySecret");
var orders = await woltPartnerClient.Orders.GetOrdersAsync();
```

Of Drive API usage:

```c-sharp
using WoltDriveClient woltDriveClient = new("mySecret");
var deliveries = await woltDriveClient.GetDeliveries("myVenue");
```
