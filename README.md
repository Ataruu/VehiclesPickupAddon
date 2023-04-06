# VehiclesPickupAddon
An open-source addon for the Minecraft plugin Vehicles that allows you to modify whether you can pick up vehicles or not.

Original [plugin](https://www.spigotmc.org/resources/%E2%9C%88%EF%B8%8Fvehicles-no-resourcepacks-needed.12446/) is by Pollitoyeye, I did **NOT** make the Vehicles plugin, I only made an addon for it utilizing its API.

## Configuration
The configuration applies to the config file of this plugin, not Vehicles. 

To disable vehicle pickup:
```
allow<vehicle name>Pickup: false
```
Example: `allowHelicopterPickup: false`
If you want to override the restriction, you can use the permission ``vehicles.pickupoverride``.

Furthermore, you can display a message when picking up was denied with `sendMessageOnDeniedPickup: true`.
