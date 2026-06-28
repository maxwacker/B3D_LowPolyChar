# LowPolyCharacter 

## Head & Torso
https://www.youtube.com/watch?v=Gqe5xeXjofo
## 00:10 Cube to head
    Edit Mode, Subdiv OP
    Smoohtness to 1.0
    
    Left side, down-left vert selection, propEdit
    Give head profile shape.
    
## 00:50 Neck
    Face select borth neck base quads
    extrude and grab to vertical
    
## 01:00 Neck adjustment
    Plan neck base : S Z 0
    Neck front adjustment
    
## 01:55 Torso Top
    Readjust & Extrude
    Extrude again (2x)
    
## 02:05 Shoulder Refine
    Add LoopCut
    Select bottom resulting face loop
    Resscale width (S X) 
    Move Center vert a bit up
    <Fix Shoulder>
    Add another LoopCut down Breast
    
## 02:25 Torso Bottom
    Extrude for hip
    Elarge on width (S X)

## 02:35 Side Back Bone curve  
    Select belly face loop
    
## 02:40 Finally remove (dissolve) Sub breath loop
    Alt-Select, X Dissolve
    Then move down breath loop a bit
    
Readjust Neck a bit

# Part 2: Few  Usefull tools
https://www.youtube.com/watch?v=XCkYRCCTbzk

## 00:00 Delete half, redone by mirroring
    Face select remove half
    Remove faces
    Add Mirro modifier
    with clipping
    (could be done quicker with automirro addon
    
## 01:20 Loop Tools
    Shearch LoopTools in AddOns <It's in Extensions now>
    Use it by
        1- Add extra loop to shoulder/breath (the one finally deleted in part 1)
        2- Select Arms start faces, RMD Menu / LoopTolls / Circle 
        
## 01:35 Extrude Arms

# Part3 : Hands, Legs and feet
https://www.youtube.com/watch?v=3JT7cCz_Yi0

## Hand as new Object
    Shift-A cube
    Edit Mode, Use LooCut to 3 & 2 on X & Z axis
    
## 00:30 Shaping Palm
    Edge selection, Reshpae top (fingers side)
    Rescale bottom faces (wrist side)
    
    Select 4 top faces (fingers bases)
    RMB-Menu / Extrude individual Faces
    Let new faces fit original one by RMB validation
    
    Now Change 'Transform Pivot Point' to individual origin
    Then scale the newly created faces
    And move them up a bit
    
## 01:20 Extruding Fingers
    Extrude on Z
    Adjust tips by Z 0
    Adjust each fingers 1by1
    
## 01:35 Fingers Segments
    Add 2 loopcuts for each finger
    
## 01:45 Finger curving
    Fingers tips face selected
    PropEdit 'Connected only'
    
## 02:00 Finger Refinment 
    Add Edge Loop arount
    Select inside edge of fingers tips.
    Double G to refine thumbs (while tracking adjacent edges direction)
    
    Move Middle inner face 
    
## 02:15 Fingers thickness refinement
    Select finger top faces
 /!\Then extend selection by CTRL-Numpad+
    Rescale XY only (by shift-Z) 
    
    Select Center edge loop of each individual finger
    Rescale XY only (schift-Z) 
    
## 02:25 Thumb
    Difficult : Extrusion Grab, Rotate
    
## 02:50 Rounding fingers
    Shift-Alt Select 'corner' Edge, Gx2 to move along perpendicular edge direction
     
## 03:00 Wrist
    <Had Resacle whole mode to increase hand thikness>
    Select 4 inner (quad) faces and extrude (rem : seme face count as arm for bridging)
    Adjust both side egdes
    
    Make wirst circle with LoopTools
    Rescale bigger X

## 03:35 Join Hand to body
    Select Hnad, then Body, Then CTRL-J
    
## 04:00 Legs
    Add 2 LoopCut
    Extrude / Reshape
    Tricks Extruce unaligned resulting faces and Exclude then SZ realign
    
    LoopTool/Circle the legs hexagon
    Rotate bit to get hexagon axix on body axis
    
## 04:35 Back 

## 04:45 Extend Legs
    Move down <not extruding>
    Rescale
    Same Process again :
        Grab to Long Legs then loopCut resacle for shaping 
        
## 05:00 Adjusting side

## 05:10 Legs
