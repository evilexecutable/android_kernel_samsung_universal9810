# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_CAMERA_RNS_V07) += exynos/exynos9810.dtb
dtbo-$(CONFIG_CAMERA_RNS_V07) += samsung/exynos9810-r7_eur_open_05.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
