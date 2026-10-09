ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
    dtbo-$(CONFIG_ARCH_KONA) += \
        kona-pdem10-overlay.dtbo \
        kona-pdem30-overlay.dtbo \
        kona-pedm00-overlay.dtbo

    kona-pdem10-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
    kona-pdem30-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
    kona-pedm00-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
