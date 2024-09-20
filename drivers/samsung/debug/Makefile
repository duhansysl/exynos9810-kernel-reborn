# drivers/samsung/debug/Makefile
#
# Copyright (c) 2010-2011 Samsung Electronics Co., Ltd.
#		http://www.samsung.com/
#
# Licensed under GPLv2

obj-y				:=
obj-m				:=
obj-n				:=
obj-				:=

# Samsung TN Debugging Features
obj-$(CONFIG_SEC_DEBUG)              += sec_debug.o
obj-$(CONFIG_SEC_DEBUG)              += sec_debug_test.o
obj-$(CONFIG_SEC_DEBUG)              += sec_debug_hard_reset_hook.o
obj-$(CONFIG_SEC_DEBUG_UPLOAD)       += sec_debug_upload.o
obj-$(CONFIG_SEC_DEBUG_RESET_REASON) += sec_debug_reset_reason.o
obj-$(CONFIG_SEC_DEBUG_EXTRA_INFO)	+= sec_debug_extra_info.o
obj-$(CONFIG_SEC_DEBUG_HW_PARAM)	+= sec_debug_hw_param.o
obj-$(CONFIG_SEC_DEBUG_AUTO_SUMMARY)	+= sec_debug_auto_summary.o
obj-$(CONFIG_SEC_DEBUG_INIT_LOG)      += sec_debug_init_log.o

obj-$(CONFIG_SEC_DEBUG_LAST_KMSG)	+= sec_debug_last_kmsg.o
obj-$(CONFIG_SEC_DEBUG_PPMPU)		+= sec_debug_ppmpu.o
obj-$(CONFIG_SEC_DEBUG_UBSAN)	+= sec_debug_ubsan.o
obj-$(CONFIG_SEC_DEBUG_KASAN)	+= sec_debug_kasan.o
obj-$(CONFIG_SEC_DEBUG_BRANCH_VERIFIER)	+=sec_debug_branch_verifier.o

