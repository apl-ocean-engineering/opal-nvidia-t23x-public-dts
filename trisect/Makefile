DTC_FLAGS += -@

old-dtb := $(dtb-y)
old-dtbo := $(dtbo-y)
dtb-y :=
dtbo-y :=
makefile-path := t23x/nv-public/trisect


dtb-y += tegra234-p3767-0000-trisect.dtb
dtb-y += tegra234-p3767-0005-trisect.dtb

# We aren't using an overlay to "enable" the cameras at runtime
# Instead they are always enabled in the base dts.
#
# So this overlay isn't doing anything right now
#
#dtbo-y += tegra234-p3767-camera-trisect-dual-avt.dtbo

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif
ifneq ($(dtbo-y),)
dtbo-y := $(addprefix $(makefile-path)/,$(dtbo-y))
endif

dtb-y += $(old-dtb)
dtbo-y += $(old-dtbo)
