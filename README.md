# AGOL_Popup_Related
Short Arcade expression for displaying related records in AGOL webmap popups.

Created for the IGS active fault database, which has a primary feature class and a standalone table of references, which are related through a relationship class. Each fault feature can have multiple associated references. The goal is to display all the feature class attributes as well as a list of references.

In the "modern" map view of AGOL, this expression only works when added in the fields list. It does not work when added as a separate Arcade element. I'm not sure why this is the case.

The expression works, but currently does not recognize the reference URLs as links. I'm exploring some options to fix this and will update the expression.
