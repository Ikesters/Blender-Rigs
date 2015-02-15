
RIG NAME   : Lieutenant Dan
VERSION    : 1.1.0
LAST UPDATE: 02/15/2015

AUTHORS:
    - Matt Ornstein (http://mattornstein.com/ ) *Original MAYA Version*
    - Brian Raschko (www.braschko.blogspot.com) *Blender 2.71 Port*

DESCRIPTION:
    Lieutenant Dan is a simple bipedal ball with an optional tail accessory.


License:
    **I do not claim copyright over the source material or exported geometry.
    **Rig ported and distributed with permission from Matt Ornstein.

    **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International
    **http://creativecommons.org/licenses/by-nc-nd/4.0/


ORIGINAL MAYA FEATURES:
   - Root Mover
   - Body mover
   - Rim Mover
   - Body squash n' stretch (Up and down only)
   - FK tail which can be hidden
   - IK legs:
        + Both leg joints stretch as a whole
        + Auto stretch: Stretch the leg to match where the foot is
        + Roll        : Rock the foot forwards and back *Limited Motion*
        + Toe Bend    : Rotates the toe up or down
        + Ball Twist  : Twist the foot on its ball
        + Toe Twist   : Twist the foot on its toe

BLENDER+ FEATURES:
   - Extra Body/Hips Mover
   - Global pivot mover
   - Tail can be repositioned on the body
   - FK legs:
        + Geometry and controls can be hidden INDEPENDENTLY
        + Both limb segments can be RESIZED INDEPENDENTLY
        + Origin point can be repositioned
        + Space switching between root and body
   - IK legs:
        + Geometry and controls can be hidden INDEPENDENTLY
        + Both leg joints can be RESIZED INDEPENDENTLY
        + Origin point can be repositioned
        + Foot twisting at heel
        + Indepenent controls for both the toe and heel
        + Knee pinning

KEYING SETS:
    - All controls: Key every control on Lieutenant Dan


KNOWN ISSUES:
    - Translating ctrl_floatPivot rotating and then moving that control again..
      will result in erratic translations of ctrl_COG.
      *Some counter animation is required if this situation arrises*