ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
    dtbo-$(CONFIG_ARCH_SM8150) += \
		sm8150-guacamole-overlay.dtbo \
		sm8150-guacamoleb-overlay.dtbo \
		sm8150-hotdog-overlay.dtbo \
		sm8150-hotdog-overlay-second.dtbo \
		sm8150-hotdogb-overlay.dtbo \
		sm8150-hotdogb-overlay-second.dtbo \
		sm8150-hotdogg-overlay.dtbo \
		sm8150-hotdogg-overlay-second.dtbo

    sm8150-guacamole-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb
    sm8150-guacamoleb-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb
    sm8150-hotdog-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb
    sm8150-hotdog-overlay-second.dtbo-base := sm8150.dtb sm8150-v2.dtb
    sm8150-hotdogb-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb
    sm8150-hotdogb-overlay-second.dtbo-base := sm8150.dtb sm8150-v2.dtb
    sm8150-hotdogg-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb
    sm8150-hotdogg-overlay-second.dtbo-base := sm8150.dtb sm8150-v2.dtb
else
dtb-$(CONFIG_ARCH_SM8150)	+= sm8150-v2-guacamole.dtb \
	sm8150-v2-guacamoleb.dtb \
	sm8150-v2-hotdog.dtb \
	sm8150-v2-hotdogb.dtb \
	sm8150-v2-hotdogg.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
