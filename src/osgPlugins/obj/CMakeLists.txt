SET(TARGET_SRC
    OBJWriterNodeVisitor.cpp
    ReaderWriterOBJ.cpp
    obj.cpp
)

SET(TARGET_H
    OBJWriterNodeVisitor.h
    obj.h
	fast_atof.h
	objTools.h
)
#### end var setup  ###
SETUP_PLUGIN(obj)
