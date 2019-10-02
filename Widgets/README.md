# ThingsBoard_widgets
Custom IOT Solution Widgets for ThingsBoard

## WeekScheduler
Week scheduler widget for Wacnet/BACnet schedule object. Generates "weekly-schedule" JSON array/object based on user input. Read/writes the JSON data to the connected shared attribute. Day 0 in the object is bound to "Monday" in the widget. Day 6 in the array is bound to "Sunday" in the widget.

Example of JSON format:
```
[ 
    [{"time":"6:0:0.0","value":1},{"time":"17:0:0.0","value":0}],
    [{"time":"6:0:0.0","value":1},{"time":"17:0:0.0","value":0}],
    [{"time":"6:0:0.0","value":1},{"time":"17:0:0.0","value":0}],
    [{"time":"6:0:0.0","value":1},{"time":"21:0:0.0","value":0}],
    [{"time":"6:0:0.0","value":1},{"time":"17:0:0.0","value":0}],
    [{"time":"9:0:0.0","value":1},{"time":"15:0:0.0","value":0}],
    [{"time":"9:0:0.0","value":1},{"time":"15:0:0.0","value":0}]
]
```

## Dropdown Enumerated Selector
Simple configurable dropdown (key->value) selector for shared attributes

## Number Card Simplifoed
Simple nuber/value display. Look-and-feel like Number Input

## Number Input
Simple nuber/value input. Look-and-feel like Number Number Card Simplified

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/IOTSolutionsAS/IOTEnergy/tags). 

## Authors

* **Johan Åtland Førsvoll** - *Initial work* - [Bliph](https://github.com/Bliph)

See also the list of [contributors](https://github.com/IOTSolutionsAS/IOTEnergy/contributors) who participated in this project.

