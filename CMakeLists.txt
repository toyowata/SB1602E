# Copyright (c) 2025 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

add_library(SB1602E INTERFACE)

target_include_directories(SB1602E
    INTERFACE
        .
)

target_sources(SB1602E
    INTERFACE
    SB1602E.cpp
)

