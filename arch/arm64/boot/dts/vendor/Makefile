vendor := $(srctree)/$(src)

ifneq "$(wildcard $(vendor)/oplus)" ""
	subdir-y += oplus
	subdir-y += oppo
	subdir-y += realme
else
ifneq "$(wildcard $(vendor)/qcom)" ""
	subdir-y += qcom
endif
endif
