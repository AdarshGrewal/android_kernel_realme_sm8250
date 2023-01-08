# SPDX-License-Identifier: GPL-2.0-only
# Copyright (C) 2018-2020 Oplus. All rights reserved.
vendor := $(srctree)/$(src)

#ifndef OPLUS_BUG_STABILITY
#ifneq "$(wildcard $(vendor)/qcom)" ""
#	subdir-y += qcom
#endif
#else
subdir-y += qcom
ifeq ($(strip $(BRAND_SHOW_FLAG)), realme)
#realme SM8250 project
endif
#endif
