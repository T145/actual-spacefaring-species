# Actual Spacefaring Species & Civilizations

👩🏽‍🚀 Aims to add and update Stellaris content related to species!

The primary goal of this mod is to stay as aligned to vanilla content and its style as possible,
so there won't be any hyper-realistic AI images or static clipart.

If there are any mods you'd like to see updated and included, feel free to make an issue with a link to the content!

# Dev Environment Setup

1. Install [VSCodium](https://vscodium.com/) (VSCode without the telemetry).
2. Install the following plugins:
    - EditorConfig
    - [AMPL plugin](https://marketplace.visualstudio.com/items?itemName=michael-sundvick.ampl)
    - [CWTools](https://marketplace.visualstudio.com/items?itemName=tboby.cwtools-vscode)
    - [Paradox Syntax Highlighting](https://marketplace.visualstudio.com/items?itemName=tboby.paradox-syntax)
3. Change the following CWTools settings:
    - Cache: Stellaris = (current game path)

# Integrated Mods

- [Amethyst Lithoid](https://steamcommunity.com/sharedfiles/filedetails/?id=3032994038)
    - Added locale definitions
    - Registered an unused female portrait
- [Arthropods+](https://steamcommunity.com/sharedfiles/filedetails/?id=1198683782)
    - Updated with new species names
- [Trace's Rooms](https://steamcommunity.com/sharedfiles/filedetails/?id=1105112234)
    - Removed some rooms that didn't feel like they paired well with vanilla, were very SD, or had some graphical issues:
        - agency_2
        - _Renamed "atlantian\_room" to "atlantean\_room."_
        - atlantis
        - fallenminer
        - gas_miner
        - _Renamed "humanoid\_room" & "humanoid2\_room" to "humanoid\_1\_room" & "humanoid\_2\_room respectively."_
        - ice_hive
        - monestary_desert
        - monestary
        - _Renamed "monestary\_windowed\_room" to "monestary\_room."_
        - sombre
        - space_ranger_blue
        - spaceship
            - Since it's already in the game as "ethic_spaceship."
        - temple
        - watercity
        - veinhive
    - To give some more reasoning, rooms were also removed if they showed dynamic elements statically. Since Stellaris portraits are animated, having a room like "watercity" that shows fish just stuck in water doesn't feel realistic. I like to give these rooms the "Zoom call test," where if I were in a digital call with one of these species and saw their uncensored backdrop would the room I'm inspecting be what I'd see live.
    - Gave more realistic restrictions to certain rooms, such as having to be anthropoid to gain access to the "arachnoid" room.
    - Fixed the "ascended_spiritualist_room" registration logic.

## WIP

- [Twink's Species](https://steamcommunity.com/sharedfiles/filedetails/?id=2079418099)
