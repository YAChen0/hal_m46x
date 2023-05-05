# SPDX-License-Identifier: Apache-2.0
#
# Copyright (c) 2023 Nuvoton
# Author: YAChen <yachen0@nuvoton.com>

add_subdirectory_ifdef(CONFIG_SOC_SERIES_M48X m48x)
add_subdirectory_ifdef(CONFIG_SOC_SERIES_M46X m46x)		#add by YAC