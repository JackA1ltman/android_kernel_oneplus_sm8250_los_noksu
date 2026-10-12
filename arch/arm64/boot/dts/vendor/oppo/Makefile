ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
    dtbo-$(CONFIG_ARCH_KONA) += \
        kona-pdem10-overlay.dtbo \
        kona-pdem30-overlay.dtbo \
        kona-pedm00-overlay.dtbo
endif

always		:= $(dtb-y) $(dtbo-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
