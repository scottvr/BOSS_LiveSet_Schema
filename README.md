# BOSS_LiveSet_Schema
JSON Schema for BOSS TSL LiveSet file format
Reversed from factory sy-300 preset patches.

Basically, 
    a TSLFile contains 
      LiveSetData, 
      a patchList (which contains
        patches, which contain
          2327 named params - which hold bytes (37 of these params contain arrays of bytes) and 
          chain params (the order of the effects chain))
    

NB: This is a first stab, generated based on what is in the factory presets. I don't know yet what other optional properties might exist, but just weren't set in any of the default patches. Also, I don't actually have an SY-300; I have a GR-55 and started down this path to see how similar the devices are, and create a parameter/FX map between the two to create a patch converter where appropriate. Feel free to share existing documentation or additions/corrections.  
