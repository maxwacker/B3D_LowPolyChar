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

## 05:10 Foot

## 05:50 Hand Join

## 06:30 Final Tweaks
    Torso enlargement
    Head reduce
    Torso
    Arms ...

## 06:50 Extra Edge at articulations for better deform in animation
    By beveling : Mid Arm Loop select, Cmd+B
    One more Loop by LoopCut
    
### 07:50 Knees loop cut & adjustment
    /!\ Move verts along egde : GG (G twice)

### 06:38 Finger articulation refinment 
    /!\ <NOT DONE>
    
### 6:40: Shoulder Refinement
    Add LoopCut and scale it up a bit, Grab it up a bit
    Grab up a bit top shouild edges 
    
# Part 4 : Rigging & Anim
https://www.youtube.com/watch?v=a6-rEXUo7-U&t=12s

< Reposition/Rescale/ApplyTransfo>
Add Armature

## 00:19 Make Armature always visibile (Front)
    Armature Panel / ViewportDisplay / Front
    
## 0:45 Reduce 1st bone 
    0.8m
    Duplicate : Select whole bone, shift-D
    Move duplicated to ass  bottom level.
    
    Original left at ground (root bone)
    New one is 'Hip' Bone
    
    Side View Adjust Hip bone

## 1:17 : Spine by Extrudingnew bone from Hip
    Each new bone being a child of extruded one.
    Parent/Child connection : Pose Mode Parent anim affects child  
    
## 1:35 : Arm bones
    Front View
    
### 01:40 Seems bone orientation is important here (but not clear how)
    CTRL-R on bone to orient bone)
    <seems bone face should be oriented front>

## 01:50 : Neck bones

## 01:55 : Legs bones
    Front View : Duplicate hip & rotate 180
    Side View : Extrude more 
    Front : Adjuct bones to center of leg
    
## 02:15 Parenting leg to hip
    Bone can parent/chilg relation even if not colose ro each other
    Select leg 1st (top) bone,  shift-select hip (remmber last is parent)
    Cmd-P (Parent) KeepOffset 
    Check dotted line goes from parent-tip to child-base
    
## 02:40 Bones naming
    Select hip bone, go to bone panel, name it 'Hip'
    Spine1, Spine2, Neck, Head
    Shoulder.L, Arm.L, Forearm.L, Hand.l
    Leg.L, Knee.L, Shin.L, Foot.L
    Root
    
    Make Root parent of Hip (Keep Offset)
    
## 03:08 Create right side
    Select Leg & Arm
    RMB-Menu / Names / Auto-Name Left/Right 
    <Not needed since i named them .L my self>
    
    Create tight side :
    Select All bones, RMB-Menu Symmetrize
    
## 04:15 IK adjustement
/!\ Clicking the X at bottom right of viewport will now symmetrize all actions

    Top View, drag elbows back a little (to get a well diefined angle for IK)
     
## 04:30 Fingers Riging <NOT DONE>

## 06:50 Armature done
    Back to Object mode
    Select Model, then Armature (MAke sure armature is the active 'yellow' object)
    CMD-P With Automatic weight
    A new modifier appears on the model
    
    
## 07:25 Armature Pose Mode
    Select Armature, CTRL-Tab (Pose Mode)
    Selection/Moving (Rotating) bone now affects the Mesh
    
    Test each bone. If something moving weirdly, back to Edit mode on bone
    
/!\ EveryTime modifications made on armature, Parenting (Auto-Weight))needs to be reset

## 08:10 Fixing 'Side of Torso moving with arm'
    To Fix, we'll add extra bone : Duplicate Shoulder
    Reduce and orient forward
    Reset Model->Armature Parenting (with auto-weight) 
    
## 09:10 Time to animate
    In Blender animations are made in Pose Mode
    In this mode, we can select bone, move (rotate) them like in Edit Mode.
    But in Pose Mode these changes are not permanent: By Atl G/R/S we can set bone back to its defaults postion
     
### 10:45 Timeline
    Adjust Pose
    Select all bone (in Pose Mode)
    I (insert) Rotation
    
    Move Anim Cursor to Frame 10, Mirror Copy Pose
    Move Anim Cursor to Frame 20, Copy Frame 1 Pose