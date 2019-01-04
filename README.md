# osg_binary_win64
- Release version of OpenSceneGraph 3.6.3 in Windows with MSVC2017 x64 + Documentation
- Release version of osgQt master 04/23/2018 + Documentation
- Release version of VirtualPlanetBuilder master 03/12/2018
# Environment Setup
- Add `OSG_ROOT`, `SOG_DIR`, `OSG_LIB_DIR`, `OSG_BIN_DIR` environment variable that point to repository
- Add `OSG_INCLUDE_DIR` environment variable that point to include directory
- Add `OSG_PLUGINS_LIB_DIR`, `OSG_PLUGINS_BIN_DIR` environment variable that point to /repository/osgPlugins-3.6.3 directory
- Append /repsitory/ and /repository/osgPlugins-3.6.3/ address to `PATH` 
# Test OSG
- Run osgversion and then you can see OSG version (OpenSceneGraph Library 3.6.3)
# OpenSceneGraph-Data Repository
This repository consist of example models and shader collection for the OpenSceneGraph 
- Clone OpenSceneGraph-Data repository (https://github.com/openscenegraph/OpenSceneGraph-Data.git)
- Add `OSG_FILE_PATH` environment variable that point to repository 