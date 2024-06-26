# FM-Inventory Forked PS-Inventory

Future updates will be coming and we will of course support all normal monitor sizes.

# Previews

### Full Inventory

![image](https://media.discordapp.net/attachments/1091065495475724368/1220142632454459472/image.png?ex=660ddd60&is=65fb6860&hm=b2f6358e7d41cec6690b921f76b518afeb05b0e5945f3b06d760c2fe48407c5f&)

### Options Menu

![image](https://media.discordapp.net/attachments/1091065495475724368/1220143764836843670/image.png?ex=660dde6e&is=65fb696e&hm=85e35c992e8988eee94dd2926e4cf8e12d444cd9748cb5e8e131a3bb85f91fc5&)

### Hotbar Slots

![image](https://media.discordapp.net/attachments/1091065495475724368/1220143921468932136/image.png?ex=660dde94&is=65fb6994&hm=3beda3fc8aba50e140a0683dbfa6647beadf9192e31c7bbf8c11baa6393f715e&)

### Inventory Glovebox

![image](https://media.discordapp.net/attachments/1091065495475724368/1220143235586854942/image.png?ex=660dddf0&is=65fb68f0&hm=92a396f3a2ab22579151d6539b81d56e8cf0b57ce53bd06b7ca39ccd3c3498aa&)

### Inventory Trunk

![image](https://media.discordapp.net/attachments/1091065495475724368/1220143441229516800/image.png?ex=660dde21&is=65fb6921&hm=11046b501963c2b19ab5b6090f5a99a25b0c5b092f8901bb01867de4cc54343f&)

# Key Features

* ALL IMAGES FOLLOW THE SAME DIMENSIONS
* Easy Photoshop guideline template for creating custom images within ps-inventory
* Custom brand logo above option buttons
* Options menu
* Help box 
* Custom inventory images (more always being added in each new update)
* Default weight icon easily changeable with Font Awesome icons
* Hotkey numbers visible in inventory and hotbar slots
* Weight progress bar
* Tooltip has a determined height (so it won't ever go higher than visible or cut off)
* Text overflow ellipsis used (so your product titles will never overlap the containers and instead do "...")
* Blurred inventory background
* Elements of NoPixel 3.5 design ideas interwoven
* Vehicle Weight In Config
* Cash Show In Info Bar


# How to install FM-Inventory (Latest QBCore Update)

* Download `FM-Inventory` from our GitHub
* Make sure you have the latest update of [qb-core](https://github.com/qbcore-framework/qb-core)
* Make sure you have the latest update of [qb-smallresources](https://github.com/qbcore-framework/qb-smallresources)
* Make sure you have the latest update of [qb-weapons](https://github.com/qbcore-framework/qb-weapons)
* Drag `FM-Inventory` into your resources folder or any subfolder
* Make sure that the folder is named `FM-Inventory` and **not** `FM-Inventory`
* Replace all occurrences of `FM-Inventory` with `FM-Inventory`.<br>The example below uses Visual Studio Code to replace all instances.

![image](https://media.discordapp.net/attachments/1147654379311202346/1176960109360971807/image.png?)

## Set up the decay system

If you want the decay system to work, then please read the information below, otherwise it won't work.

You need to add a decay value for all items in your `qb-core/shared/items.lua` file, the variable stands for the number of days it takes to decay.

### Examples:

#### Example of what you have to add

```lua
-- decay = The number of days it takes for an item to decay
-- delete = If set to true, the item will be removed once it decays
["decay"] = 28.0, ["delete"] = true
```

#### Example with the full item in QB-Core's shared file

```lua
['sandwich'] = {['name'] = 'sandwich', ['label'] = 'Sandwich', ['weight'] = 200, ['type'] = 'item', ['image'] = 'sandwich.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true,	['combinable'] = nil, ['description'] = 'Nice bread for your stomach', ["decay"] = 3.0, ["delete"] = true},
```

In this example, the sandwich item would take 3 days to decay and once it does, it would be removed.

# Dependencies

* [qbcore framework](https://github.com/qbcore-framework)
* [qb-target](https://github.com/BerkieBb/qb-target)
* [qb-core](https://github.com/qbcore-framework/qb-core)
* [qb-logs](https://github.com/qbcore-framework/qb-logs)
* [qb-traphouse](https://github.com/qbcore-framework/qb-traphouse)
* [qb-radio](https://github.com/qbcore-framework/qb-radio)
* [qb-drugs](https://github.com/qbcore-framework/qb-drugs)
* [qb-shops](https://github.com/qbcore-framework/qb-shops)

## Performance

Runs at ~ 0.00 to 0.01 ms if you have more optimization suggestions feel free to reach out

# Orginal Credits

* [Project Sloth](https://github.com/Project-Sloth)

# Issues and Suggestions

Please use the GitHub issues system to report issues or make suggestions, when making suggestions, please keep [Suggestion] in the title to clarify that it is a suggestion.

## Connect with us

Join our [**Discord**](https://discord.gg/4FRMWEw98Z) for updates, support, and special early testing!
