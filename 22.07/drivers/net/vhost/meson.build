# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2018 Intel Corporation

if is_windows
    build = false
    reason = 'not supported on Windows'
    subdir_done()
endif

deps += 'vhost'
sources = files('rte_eth_vhost.c')
headers = files('rte_eth_vhost.h')
