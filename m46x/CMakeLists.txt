# SPDX-License-Identifier: Apache-2.0
#
# Copyright (c) 2023 Nuvoton
# Author: YAChen0 <yachen0@nuvoton.com>

zephyr_include_directories(StdDriver/inc)
zephyr_include_directories(Devices/M460/Include)

zephyr_sources_ifdef(CONFIG_SOC_SERIES_M46X Devices/M460/Source/system_M460.c)

add_subdirectory(StdDriver)
