INCLUDE_DIRECTORIES(${OSG_INCLUDE_DIRS} )
SET(TARGET_LIBRARIES_VARS OSG_LIBRARY OSGDB_LIBRARY OSGGA_LIBRARY OSGUTIL_LIBRARY OSGVIEWER_LIBRARY OSGSIM_LIBRARY OSGSHADOW_LIBRARY OSGTEXT_LIBRARY OSGMANIPULATOR_LIBRARY OPENTHREADS_LIBRARY)

SET(TARGET_SRC osgearth_simple.cpp )

#### end var setup  ###
SETUP_APPLICATION(osgearth_simple)
