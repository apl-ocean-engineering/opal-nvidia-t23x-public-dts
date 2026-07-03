DTC_FLAGS += -@

old-dtb := $(dtb-y)
old-dtbo := $(dtbo-y)
dtb-y :=
dtbo-y :=
makefile-path := t23x/nv-public/alliedvision

dtbo-y += tegra234-p3767-camera-p3768-alvium-dual-19623-1x2-1x4.dtbo
dtbo-y += tegra234-p3737-camera-dual-alvium-19616-2x4-overlay.dtbo
dtbo-y += tegra234-p3767-camera-p3768-alvium-dual-19623+19502-1x2-1x4.dtbo
dtbo-y += tegra234-p3767-camera-p3768-alvium-dual-19623+19558-1x2-1x4.dtbo
dtbo-y += tegra234-p3767-camera-forecr-ornx-alvium-dual-19623-2x4.dtbo
dtbo-y += tegra234-p3767-camera-forecr-ornx-alvium-dual-19623+19558-2x4.dtbo
dtbo-y += tegra234-p3767-camera-forecr-ornx-alvium-dual-19623+19502-2x4.dtbo
dtbo-y += tegra234-p3737-camera-dual-alvium-19616+19502-2x4-overlay.dtbo
dtbo-y += tegra234-p3737-camera-dual-alvium-19616+19558-2x4-overlay.dtbo
dtbo-y += tegra234-p3737-camera-dual-alvium-19616+19558-2x4-single-deser-overlay.dtbo
dtbo-y += tegra234-p3767-camera-forecr-ornx-alvium-dual-19623-dual-14384-4x2.dtbo
dtbo-y += tegra234-p3767-camera-forecr-ornx-alvium-dual-19623-single-14384-1x4-2x2.dtbo

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif
ifneq ($(dtbo-y),)
dtbo-y := $(addprefix $(makefile-path)/,$(dtbo-y))
endif

dtb-y += $(old-dtb)
dtbo-y += $(old-dtbo)
