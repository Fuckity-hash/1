First-person Model (Bedrock approximation)

How to import:
- Double-click FirstPersonModel_Bedrock.mcaddon (generated below) or import RP/BP .mcpack files individually.
- Enable the Behavior Pack in your world; the Resource Pack will auto-enable via dependency.

Usage in-world:
- Run: /function firstperson/enable to switch to the custom camera preset.
- Run: /function firstperson/disable to revert to default first person.

Notes:
- Bedrock cannot truly render your full body in first-person like the Java mod. This pack approximates the perspective via a camera preset.
- You may need to enable 'Camera' experimental features and use latest 1.21.x where /camera presets are supported.
- Depending on engine version, the cameras.json schema keys may require adjustment (inherits_from vs inherit_from, etc.). If the camera doesn't apply, update to latest Bedrock or let me know your exact version.

License:
- Original Java mod 'First-person Model' by tr7zw is MIT-licensed. This Bedrock pack contains no Java code and uses only the icon for identification.
