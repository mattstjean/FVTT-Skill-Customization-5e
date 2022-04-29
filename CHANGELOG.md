# CHANGELOG

## [2.4.0] 2022-04-29

- Add compatibility for Foundry v9 (MattStJean)

## [2.3.0] 2021-01-16

### CHANGED

- Use libWrapper for more robust compatibility with other modules.
- Bump core compatible version.

## [2.2.0] 2020-12-20

### API

- Return the result from the monkey-patched Actor5e#rollSkill so that it can be used "downstream" (Thanks CarlosFdez for the suggestion).

### CHANGED

- Bump compatible core version.

## [2.1.1] 2020-09-30

Double check compatibility with core foundry 0.7.3 and dnd5e 0.9.6.

### CHANGED

- Ensure that when "0" or "-" is entered for a skill bonus, the flag for that skill is unset and the sheet displays "-".

## [2.1.0] 2020-07-29

### FIXED

- Fixed an issue where the passive score for a skill would be calculated incorrectly if the actor had the "observant feat" option enabled in special traits.

## [2.0.0] 2020-07-20

This update is compatible with dnd5e 0.9.4 and up *ONLY*.

### CHANGED

- Add compatibility for dnd5e 0.9.4.
- Make it hopefully Forge Bazaar compatible?

## [1.3.0] 2020-06-23

### ADDED

- Update core compatible version to 0.6.4.
- Allow for roll bonuses.

### FIXED

- Fix some additional layout issues with Tidy5e sheet on Firefox.
- Remove language definitions in manifest (this mod doesn't add any text, so no need for translations).

## [1.2.2] 2020-06-22

### FIXED

- Fix layout issues with Tidy5e sheet (both pc and the new npc sheets).

## [1.2.1] 2020-06-04

### ADDED

- The skill bonus text box will now select its contents when focused. This will make it easier to quickly edit a skill bonus.

### FIXED

- Fix an issue where skills would be cut off the bottom of the skill list in Tidy 5e (thanks kleelue for the report!).

## [1.2.0] 2020-06-13

### ADDED

- Add formatting support for Sky's Alt 5e sheet. Previously there was some layout issues with this sheet, this has been resolved.

## [1.1.0] 2020-06-13

### ADDED

- Add formatting support for Tidy5e Sheet. Previously there was some layout issues with this sheet, this has been resolved.

## [1.0.1] 2020-06-13

### FIXED

- Fixed passive scores not being updated with the extra bonus.

## [1.0.0] 2020-06-13

### ADDED

- Added text boxes which allow for adding a flat bonus to each individual skill roll.
- Added selection menu to allow selection of base ability score for each individual skill roll.
