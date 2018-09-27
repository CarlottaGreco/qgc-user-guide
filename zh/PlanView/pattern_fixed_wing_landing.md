# Fixed Wing Landing Pattern (Plan Pattern)

The *Fixed Wing Landing Pattern* tool allows you to add a fixed wing landing pattern to a mission. It is supported on all autopilots.

![Fixed Wing Landing Pattern](../../assets/plan/fixed_wing_landing_pattern.jpg)

The first point of the pattern is a loiter point with a specific altitude and the second is a landing point. The vehicle will loiter at the first point until it reaches the target altitude, and then begin the landing sequence to fly down to the specified landing spot.

Both the loiter and land points can be dragged to new positions, and a number of other settings can be configured in the associated mission item.

## Creating a Landing Pattern

To create a landing pattern:

1. Open [PlanView](../PlanView/PlanView.md) *Plan Tools*).
2. Choose the *Pattern Tool* from the *Plan Tools* and then select *Fixed Wing Landing Pattern*.
  
  ![Fixed Wing Landing Pattern](../../assets/Plan/fixed_wing_landing_pattern_menu.jpg)
  
  This will add a *Landing Pattern* item to the mission list (on the right).
  
  ![Fixed Wing Landing Pattern](../../assets/Plan/fixed_wing_landing_pattern_mission_item_initial.jpg)

3. Click on the map to create both the loiter and landing points. These can be moved on the map.

Additional settings are covered in the next section.

## Settings

The landing pattern can be further configured in the associated mission item (in the mission item list on the right hand side of the Plan View).

### Loiter Point

The *Loiter Point* settings are used to configure the loiter altitude, radius and direction.

![Landing Pattern - Loiter Point](../../assets/Plan/fixed_wing_landing_pattern_settings_loiter.jpg)

The configurable options are:

- **Altitude** - Loiter altitude.
- **Radius** - Loiter radius.
- **Loiter clockwise** - Check to loiter in a clockwise direction (anti-clockwise is the default). 

### Landing Point

The *Landing Point* settings are used to configure the landing position and path.

![Landing Pattern - Landing Point](../../assets/Plan/fixed_wing_landing_pattern_settings_landing.jpg)

The configurable options are:

- **Heading** - Heading from loiter point to land point.
- **Altitude** - Altitude for landing point (nominally zero).
- *Radio Buttons* 
  - **Landing Dist** - Distance between loiter and landing points.
  - **Glide Slope** - Glide slope between loiter and landing points.
- **Altitudes relative to home** - Check to set all altitudes in mission item to be relative to home (default is AMSL).