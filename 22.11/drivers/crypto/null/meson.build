# SPDX-License-Identifier: BSD-3-Clause
# Copyright(c) 2017 Intel Corporation

if is_windows
    build = false
    reason = 'not supported on Windows'
    subdir_done()
endif

deps += 'bus_vdev'
sources = files('null_crypto_pmd.c', 'null_crypto_pmd_ops.c')
pmd_supports_disable_iova_as_pa = true
