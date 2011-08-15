# Copyright (C) 2011 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT (lua-pythonic-optparse NONE)
CMAKE_MINIMUM_REQUIRED (VERSION 2.6)
INCLUDE ( dist.cmake )

install_lua_module ( pythonic.optparse module/lmod/pythonic/optparse.lua )
install_data ( COPYRIGHT )

