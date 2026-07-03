DTC_FLAGS += -@

old-dtb := $(dtb-y)
old-dtbo := $(dtbo-y)
dtb-y :=
dtbo-y :=
makefile-path := t23x/nv-public/antmicro

dtb-y += tegra234-p3767-0000-antmicro-job.dtb
dtb-y += tegra234-p3767-0001-antmicro-job.dtb
dtb-y += tegra234-p3767-0003-antmicro-job.dtb
dtb-y += tegra234-p3767-0004-antmicro-job.dtb
dtb-y += tegra234-p3767-0005-antmicro-job.dtb
dtb-y += tegra234-p3767-0000-antmicro-job-ov9281.dtb
dtb-y += tegra234-p3767-0001-antmicro-job-ov9281.dtb
dtb-y += tegra234-p3767-0003-antmicro-job-ov9281.dtb
dtb-y += tegra234-p3767-0004-antmicro-job-ov9281.dtb

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif
ifneq ($(dtbo-y),)
dtbo-y := $(addprefix $(makefile-path)/,$(dtbo-y))
endif

dtb-y += $(old-dtb)
dtbo-y += $(old-dtbo)
