# SPDX-License-Identifier: Apache-2.0
#
# Copyright (c) 2023 Nuvoton
# Author: YAChen <yachen0@nuvoton.com>

zephyr_library_sources_ifdef(CONFIG_HAS_NUMICRO_HAL src/sys.c)

zephyr_library_sources(src/clk.c)
zephyr_library_sources(src/gpio.c)
zephyr_library_sources_ifdef(CONFIG_HAS_NUMICRO_UART src/uart.c)
