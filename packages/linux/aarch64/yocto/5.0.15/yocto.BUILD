# *******************************************************************************
# Copyright (c) 2025 Contributors to the Eclipse Foundation
#
# See the NOTICE file(s) distributed with this work for additional
# information regarding copyright ownership.
#
# This program and the accompanying materials are made available under the
# terms of the Apache License Version 2.0 which is available at
# https://www.apache.org/licenses/LICENSE-2.0
#
# SPDX-License-Identifier: Apache-2.0
# *******************************************************************************

"""Build file for GCC external package"""

package(default_visibility = ["//visibility:public"])

filegroup(
    name = "all_files",
    srcs = glob(["*/**/*"]),
)

filegroup(
    name = "sysroot_files",
    srcs = glob(["sysroots/**/*"]),
)

filegroup(
    name = "ar",
    srcs = ["sysroots/x86_64-pokysdk-linux/usr/bin/aarch64-poky-linux/aarch64-poky-linux-ar"],
)

filegroup(
    name = "cc",
    srcs = ["sysroots/x86_64-pokysdk-linux/usr/bin/aarch64-poky-linux/aarch64-poky-linux-gcc"],
)

filegroup(
    name = "gcov",
    srcs = ["sysroots/x86_64-pokysdk-linux/usr/bin/aarch64-poky-linux/aarch64-poky-linux-gcov"],
)

filegroup(
    name = "cxx",
    srcs = ["sysroots/x86_64-pokysdk-linux/usr/bin/aarch64-poky-linux/aarch64-poky-linux-g++"],
)

filegroup(
    name = "strip",
    srcs = ["sysroots/x86_64-pokysdk-linux/usr/bin/aarch64-poky-linux/aarch64-poky-linux-strip"],
)

filegroup(
    name = "sysroot_dir",
    srcs = ["sysroots/cortexa57-poky-linux"],
)

filegroup(
    name = "cxx_builtin_include_directories",
    srcs = [
        "sysroots/cortexa57-poky-linux/usr/include/c++/13.4.0",
        "sysroots/cortexa57-poky-linux/usr/include/c++/13.4.0/aarch64-poky-linux",
    ],
)
