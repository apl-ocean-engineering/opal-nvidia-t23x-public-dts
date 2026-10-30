DTC_FLAGS += -@

old-dtb := $(dtb-y)
old-dtbo := $(dtbo-y)
dtb-y :=
dtbo-y :=
makefile-path := t23x/nv-public/seeed

dtb-y += tegra234-j401-p3768-0000+p3767-0000-recomputer-super.dtb
dtb-y += tegra234-j401-p3768-0000+p3767-0001-recomputer-super.dtb
dtb-y += tegra234-j401-p3768-0000+p3767-0003-recomputer-super.dtb
dtb-y += tegra234-j401-p3768-0000+p3767-0004-recomputer-super.dtb

dtbo-y += tegra234-p3767-camera-p3768-j401-dual-vc-imx900.dtbo
dtbo-y += tegra234-p3767-camera-p3768-j401-quad-vc-imx900.dtbo


ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif
ifneq ($(dtbo-y),)
dtbo-y := $(addprefix $(makefile-path)/,$(dtbo-y))
endif

dtb-y += $(old-dtb)
dtbo-y += $(old-dtbo)
