#
# Makefile for the touchscreen drivers.
#

# Each configuration option enables a list of files.
#obj-$(CONFIG_TOUCHPANEL_HIMAX_HX83112B) += hx83112b/
obj-$(CONFIG_TOUCHPANEL_HIMAX_HX83112A_NOFLASH) += hx83112a_noflash/
obj-$(CONFIG_TOUCHPANEL_HIMAX_HX83102J_NOFLASH) += hx83102j_noflash/
#obj-$(CONFIG_TOUCHPANEL_HIMAX_HX83112B_NOFLASH) += hx83112b_noflash/

oplus_bsp_tp_himax_comnon-y += himax_common.o
obj-$(CONFIG_TOUCHPANEL_HIMAX) += oplus_bsp_tp_himax_comnon.o
#endif
#endif
