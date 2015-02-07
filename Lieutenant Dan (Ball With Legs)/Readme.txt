RIG NAME   : Lieutenant Dan
VERSION    : 1.0.0
LAST UPDATE: 02/06/2015

AUTHORS:
    - Matt Ornstein (http://mattornstein.com/ ) *Original MAYA Version*
    - Brian Raschko (www.braschko.blogspot.com) *Blender 2.71 Port*

DESCRIPTION:
    Lieutenant Dan is a simple bipedal ball with an optional tail accessory.
    Great for simple animations, or for those just learning the basics.
    
    **Though this character has been ported over to Blender by me,
    **I do not claim copyright over the source material or exported geometry.
    **However, the Blender rig setup and functions are of my own design.


ORIGINAL MAYA FEATURES:
   - Root Mover
   - Hips mover
   - Rim Mover
   - Body squash n' stretch (Up and down only)
   - FK tail which can be hidden
   - "IK Only" legs:
        + Both leg joints stretch as a whole
        + Auto stretch: Stretch the leg to match where the foot is
        + Roll        : Rock the foot forwards and back *Limited Motion*
        + Toe Bend    : Rotates the toe up or down
        + Ball Twist  : Twist the foot on its ball
        + Toe Twist   : Twist the foot on its toe

BLENDER FEATURES:
   - Root Mover
   - Global pivot mover
   - Center of gravity mover
   - Hips mover
   - Rim Mover
   - Body squash n' stretch (Up and down only)
   - FK tail which can be hidden:
        + Tail can be repositioned on the body
   - FK legs:
        + Geometry and controls can be hidden
        + Both limb segments can be RESIZED INDEPENDENTLY
        + Space switching between root and body
        + Origin point can be repositioned
   - IK legs:
        + Geometry and controls can be hidden
        + Origin point can be repositioned
        + Both leg joints can be RESIZED INDEPENDENTLY
        + Auto stretch: Stretch the leg to match where the foot is
        + Foot Rock: Rock the WHOLE FOOT forwards and back
        + Foot twisting at the toe, ball and heel
        + Indepenent controls for both the toe and heel
        + Knee pinning


KNOWN ISSUES:
    - UV's are unfinished, only the body (The Sphere) has been corrected
    
    - Translating ctrl_floatPivot rotating and then moving that control again..
      will result in erratic translations of ctrl_COG.
      *Some counter animation is required if this situation arrises*
