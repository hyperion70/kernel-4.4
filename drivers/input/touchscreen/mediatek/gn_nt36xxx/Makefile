# include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Linux driver folder
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/
ccflags-y += -I$(srctree)/drivers/misc/mediatek/include/mt-plat/$(MTK_PLATFORM)/include/
#obj-$(CONFIG_TOUCHSCREEN_NT36xxx_1080_1920)    += nt36xxx.o nt36xxx_ext_proc.o nt36xxx_fw_update.o nt36xxx_mp_ctrlram.o
obj-y += nt36xxx.o nt36xxx_ext_proc.o nt36xxx_fw_update.o nt36xxx_mp_ctrlram.o gn_tpd_feature.o
