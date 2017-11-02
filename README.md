# Bachelor
3 different lighting approaches are avaiable:
- static lighting with movable drawers/doors (Map-name: StaticOnly...)
- static lighting with static drawers/doors (Map-name: StaticNOMovable...)
- static/stationary lighting with movable drawers/doors (Map-name: StaticStationary...)

For each of these there exist three different scenarios:
- Daytime, clear sky and bright sunlight
- Daytime, overcast
- Nighttime, clear sky

# Differences between the scenarios
In every scenario exist a folder in the World Outliner with the word 'LIGHT' at the beginning, followed by the description for the lighting method and scenario. It contains the settings that are unique for that scenario.
example:
- Lights (Folder): Contains the ceiling light models that have different materials for night-/daytime
- WindowLights (Folder): Only present in the daytime-scenarios, contains the filllights in front of the windows (some of them static depending on lighting approach)
- CeilingLights (Folder): Only present in the nighttime-scenario, contains the ceiling light-sources (static/stationary depending on lighting approach)
- Atmospheric Fog: Different settings for clear sky-/night-scenarios but not present in the overcast scenarios
- Skylight: Present in the daytime-scenarios but not in the nighttime-scenarios
- DirectionalLightStationary1: Different settings for every scenario
- SM_Skysphere: Different settings in every scenario
- SM_Surround: Different settings for each approach

# Textures
- Textures Street:https://freestocktextures.com/texture/asphalt-road-street,94.html
- Grass: https://www.textures.com/download/grass0130/38953
- Window BuildingTop: https://www.textures.com/download/highriseglass0021/39843?q=window
- BuildingBricks: https://www.textures.com/download/bricksmallbrown0367/80762?q=red+brick
