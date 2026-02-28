# Sprite Layout

Canonical sprite paths are organized by object category:

- `actors/<sprite_id>.<ext>`
- `monsters/<sprite_id>.<ext>`
- `items/<sprite_id>.<ext>`
- `weapons/<sprite_id>.<ext>`
- `armor/<sprite_id>.<ext>`
- `environment/<sprite_id>.<ext>`

Runtime custom overrides are stored in:

- `custom/<category>/<sprite_id>.<ext>`

Notes:

- Sprite IDs are lowercase snake_case and match game object IDs where possible.
- The Sprite Editor writes only to `custom/` so base art stays intact.
- Adding a new object in `MONSTER_TYPES` or `ITEM_TYPES` automatically surfaces it in the Sprite Editor.
