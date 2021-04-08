# Skill Quest Prices

## **Editing Skill Prices**

![Imgur gif](https://i.imgur.com/RHUdQdE.gif)

For this example, we will be editing the file `construction.json`

The original code of the file is as follows:

```json
{
    "skill" : "Construction",
    "image" :  "https://i.imgur.com/XRTvQ9j.png",
    "checkpoints" : [
        33,
        52,
        73
    ],
    "prices" : [
        {   "start_level" : 1,
            "end_level" : 52,
            "gp/xp" : 60,
            "notes" : "Normal and oak planks"
        },
        {
            "start_level" : 52,
            "end_level" : 99,
            "gp/xp" : 20,
            "notes" : "Oak planks"
        },
        {
            "start_level" : 52,
            "end_level" : 99,
            "gp/xp" : 15,
            "notes" : "Teak planks"
        },
        {
            "start_level" : 52,
            "end_level" : 99,
            "gp/xp" : 12,
            "notes" : "Mahogany planks"
        }
    ]
}
```

### Let's change it! Below are the updated skilling prices.

```json
{
    "skill" : "Construction",
    "image" :  "https://i.imgur.com/XRTvQ9j.png",
    "checkpoints" : [
        33,
        52,
        73
    ],
    "prices" : [
        {   "start_level" : 1,
            "end_level" : 33,
            "gp/xp" : 85,
            "notes" : "Various low tier items"
        },
        {
            "start_level" : 33,
            "end_level" : 52,
            "gp/xp" : 60,
            "notes" : "Miscellaneous oak items" 
        },
        {
            "start_level" : 52,
            "end_level" : 99,
            "gp/xp" : 20,
            "notes" : "Teak planks or Mythical capes"
        },
        {
            "start_level" : 52,
            "end_level" : 99,
            "gp/xp" : 18,
            "notes" : "Mahogany tables"
        }
    ]
}
```

#### Once you are done making your edit's, hit the green "commit changes" button at the bottom and you're done.
#### Note: Don't worry about the `checkpoints` section; I will fix that myself.

## **Adding New Skill Training Method** 

![imgur gif](https://i.imgur.com/RHUdQdE.gif)

Again, I am using the `construction.json` file we edited above.
This time, I want to add a new skilling type, `oak dungeon doors`.
To add that in is very simple, see below.

```json
{
    "skill" : "Construction",
    "image" :  "https://i.imgur.com/XRTvQ9j.png",
    "checkpoints" : [
        33,
        52,
        73
    ],
    "prices" : [
        {   "start_level" : 1,
            "end_level" : 33,
            "gp/xp" : 85,
            "notes" : "Various low tier items"
        },
        {
            "start_level" : 33,
            "end_level" : 52,
            "gp/xp" : 60,
            "notes" : "Miscellaneous oak items" 
        },
        {
            "start_level" : 52,
            "end_level" : 99,
            "gp/xp" : 20,
            "notes" : "Teak planks or Mythical capes"
        },
        {
            "start_level" : 74,
            "end_level" : 99,
            "gp/xp" : 25,
            "notes" : "Oak dungeon doors"
        },
        {
            "start_level" : 52,
            "end_level" : 99,
            "gp/xp" : 18,
            "notes" : "Mahogany tables"
        }
    ]
}
```
