# Yet Another Factorio Calculator

I can't stop playing Factorio.

I know that there are ton of calculators out there for Factorio, but where's the fun if I don't make it myself?

#### Parameters
This calculator will show which producers are required to make all the components of a recipe according to the following parameters:
- Producer Quantity
- Number of Seconds to Make One of the Item
- Production / Second
- Production / Minute

Changing any one of these auto-calculates the other three.

#### Producer Types
The type of producer can be set for:
- Assembly Machines
- Furnaces
- Miners

The type of machine chosen will affect the time since some machines produce faster than others.

#### Producer Inclusion/Exclusion
Further you can include/exclude the following types of machines:
- Assembly Machines
- Chemical Plants
- Furnaces
- Miners
- Pumps
- Refineries

For instance, with miners turned off, it won't show you how many miners are required to make the required number of specified plates within the specified time.

#### Overrides
To account for beacons and modules, a static time and production bonus may be entered for:
- Assembly Machines
- Chemical Plants
- Furnaces
- Miners
- Refineries

Plug in your average speed and bonus for whichever combination of beacons and modules you are using.

#### Overhead
The overhead bars show how much excess product is created in the manufacturing time. This can be a good judge of where your bottlenecks will be and which components will be producing fast enough to sometimes be pulled somewhere else.

#### It Works as a Checklist
Checking a box in the used column will fade the contents of that row. They're still readable but they don't stand out. This is useful for when you're designing and building your factory to keep track of what you still have left to place.

#### The Component Lists
To the right of the main table are two more tables that list the components required. The lists are effectively the same, except for how they are sorted. The first is sorted according to the item to show which components are needed for a particular item. The second is sorted by component to show which items a particular component is required for.
Clicking a cell in the main table will highlight the selected component in the other two tables.

#### Updating the Database
If you want to add items or need to change their components, update or add these to the data sheet. The first table is for items and the second table is for the components of the items.
After you've finished updating them, run the `SetupData` macro to recompile the expanded component list. The calculator will not work correctly if these lists are changed and you do not run the macro.
