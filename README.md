For most of these, the object numbers will have to be changed, as the dump just pulls the object numbers over from the exporting system.
To do this you will need to use the create command at the top of the generic, replace the number in the rest of the code with the proper number.
For example, the Self Cleaning Room object number was exported as #27777.  After the initial create command in the receiving MOO, you will get the new number.
Do a Find\replace using #27777 as the find, and the new number as the replace.

You can also create a property on #0 to reference the generic easier.  For example on the Self Clearning Room, after I created it on an 
external Moo, it gave me the #238.
@property #0.gSCR "#238"

Any time you reference $gSCR it will substitute #238.
