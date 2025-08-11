# First Person Body (Resource Pack Only)

Adds visible legs and torso in first-person for added immersion. RP-only: no camera changes, no scripts.

Install
- Copy the `bedrock-first-person-rp` folder as a resource pack, or zip it to `.mcpack` and import.
- Place at the top of your resource pack stack.
- Works client-side only.

Notes
- Arms are hidden from the third-person model in first-person to avoid double hands; vanilla FP hands/items still render.
- Head/hat are hidden in first-person to prevent clipping.
- Legs and torso are forced visible in first-person via render controller conditions.
- When gliding, swimming, or riding in first person, the extra body parts are temporarily hidden to reduce camera clipping.

Compatibility
- May conflict with packs that override `controller.render.player` or `entity/player.entity.json`.
- Keep this pack above such packs.

Tested with Bedrock 1.20+. If you spot missing parts on some skins, try moving this pack to the very top or disabling other player model packs.