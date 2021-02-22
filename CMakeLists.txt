AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/GainHonorGuard.cpp")
AC_ADD_SCRIPT_LOADER("GainHonorGuard" "${CMAKE_CURRENT_LIST_DIR}/src/loader.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/GainHonorGuard.conf.dist")