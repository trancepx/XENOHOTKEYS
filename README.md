# XENOHOTKEYS
GOAL: TO CREATE A STANDARDIZED HOTKEY / MOUSE / CONTROLLER PORTABLE INPUT SYSTEM FOR INTEROPERABILITY BETWEEN SOFTWARES LIKE 3D, 2D DESIGN PROGRAMS, AND MORE.
     
     INTRO: The view navigation is one of the most important things that needs to be synchronized between applications for a fluid workflow.

     PROBLEM: Almost every single 3D software, has a completely different controls for the most important and often used ways of interacting with the program, namely - Camera controls, (Rotate, zoom, pan) and Selections/highlighting.
     SOLUTION 1: Remappable controls, at the very least, software developers should allow complete customization of all controls, and hotkeys. Including multibutton hotkeys.
     SOLUTION 2. A way or method for sharing controls between programs, across different platforms. Perhaps a .txt file, or as complex as an external program or web app that allows for a subset of controls for each program (As not all programs have the same exact functions.) This could also be extended to all software, including games, desktop publishing software, etc.

     3D work, is HIGHLY reliant on muscle memory, so when switching between different software, why isn't there a way to keep using the same basic controls across all programs?
     (Camera rotate, Zoom, Pan, SELECT, diselect... etc)
     The issue is, there is almost no way to remap these controls available to the user. The user is simply expected to use the software as is, even if it has a completely backwards control scheme from every other 3d program. This is, equivalent to car manufactuers switching the gas and the brake pedal, inverse steering, or no steering wheel at all but a joy stick? Imagine how different that would would be?
     So WHY ARE 3D PROGRAMS shipped with not only arbitrary control schemes, but almost 95% of the programs lack any way to REMAP THEM? IT's 2022, at the time of me writing this.
     I AM PETITIONING ALL SOFTWARE DEVELOPERS, to atleast offer a way to remap thier controls, at the very least, and save this as a preference file that can be backed up and re-imported.
     IT's not enough to simply provide a few different options of pre-defined control schemes, but all controls must be completely remappable, as well as fine tunable, in the speed/rate/sensitivty of rotate, zoom, pan) 
     Something universal, such as degrees rotated / screen % of mouse traveled/pixels etc.
     I suggest a universal control
     Cameral Controls (Rotate, zoom, pan),
 


# PROPOSED SCHEMA FOR 3D CAD/MODELING SOFTWARES
      views (GLOBAL PRIORITY 1)
      2d 
        x
        y
        z
        n
      3d shift+z
        o orthographic
        p perspective
      pan 2d/3d	 
        right mouse click + drag
      orbit
        middle mouse button
      zoom
        middle mouse wheel
      SAVE
        CTRL+S
      OPEN
        CTRL+O
      CLOSE	
        ALT+F4
      UNDO	
        CTRL+Z
      REDO
        CTRL+R
      SELECT ALL
        CTRL+A
      CLEAR SELECTION
        CTRL+D,SPACE
      CENTER 3D VIEW ON SELECTION AND ORBIT AROUND
        A 
      REPEAT LAST OPERATION (FOR PRIORITY 2+)
        RIGHT CLICK

      ===== SELECTION MODE TAB (PRIORITY 2)
      VERTEXS/POINTS
        TAB,V
      edges
        TAB,e
        TAB,e+shift extended edge loop
      faces/surfaces
        TAB,f
      curves
        TAB,c
      solids
        TAB,s


      OPERATIONS ON SELECTION (PRIORITY 3)

      UNDO LAST SELECTION
        TAB+Z
      REDO LAST SELECTION
        TAB+R
      Move (opens move ui element, with 3 axises)
        m
        m,x
        m,y
        m,z
      Rotate(opens rotate ui element, with 3 wheels)
        r
        right click toggle rotate type: center, axis (two points),corner
      scale
        s last scale type
        leftclick - toggle to next scale mode: corner, center,3d,2d,1d

      MIRROR 2D
        M
        CLICK FIRST POINT
        CLICK SECOND POINT
      ARRAY
        A
        CLICK TOGGLE TYPE:CIRCULAR,DIRECTIONAL,PATH
      LOFT
        L
        SELECT TWO OR MORE SEGMENTS
      REVOLVE
        SHIFT+R

      DELETE
        D, OR DELETE (can be disabled, or apply only to lines, instead of entire objects/meshes, prompt for assemblies
      GROW SEL BY 1
        +
      SHRINK SEL BY 1
        -
      CLEAR SELECTION /DISELECT
        SPACE

      flatten
        F last plane
        leftclick what plane,x,y,z,custom 3 points
 


