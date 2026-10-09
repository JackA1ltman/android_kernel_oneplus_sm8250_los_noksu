ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
    dtbo-$(CONFIG_ARCH_KONA) += \
        kona-rmx3366-overlay.dtbo \
        kona-rmx3370-overlay.dtbo

    kona-rmx3366-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
    kona-rmx3370-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
