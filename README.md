# Gary assets

Character reference sheets for [@garywhatup](https://instagram.com/garywhatup),
used as identity references for video generation.

Public so they can be fetched anonymously at generation time. These are the
identity authority for the character: face, body proportions and wig. Clothing
is specified per scene and is *not* taken from these sheets.

| File | What it locks |
|---|---|
| `sheets/body.png` | Height, proportions, silhouette, hands. **Head is 13-15% of total height.** |
| `sheets/face.png` | Facial geometry from every angle |
| `sheets/wig.png` | Wig shape from every angle, including under helmets and hats |
| `sheets/expression.png` | Expression range (hosted, not currently sent — see below) |

The expression sheet is deliberately not attached to generations. The model
averages its references, and three head sheets against one body sheet produced
a character with an oversized head.
