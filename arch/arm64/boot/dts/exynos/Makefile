dtb-$(CONFIG_ARCH_EXYNOS7) += exynos7-espresso.dtb

dtb-$(CONFIG_SOC_EXYNOS8890) += exynos8890-maestro.dtb
dtb-$(CONFIG_SOC_EXYNOS8895) += exynos8895-smdk8895.dtb
dtb-$(CONFIG_SOC_EMULATOR7872) += exynos7872-emulator7872.dtb
dtb-$(CONFIG_SOC_EXYNOS7872) += exynos7872-smdk7872.dtb
dtb-$(CONFIG_SOC_EXYNOS7872) += exynos7872-maestro7872.dtb
ifeq ($(CONFIG_SOC_EXYNOS7884),y)
dtb-y += exynos7884-universal7884.dtb
dtb-y += exynos7884-universal7884_FHD.dtb
else ifeq ($(CONFIG_SOC_EXYNOS7883),y)
dtb-y += exynos7883-universal7883.dtb
dtb-y += exynos7883-universal7883_FHD.dtb
else
dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7885-smdk7885.dtb
dtb-$(CONFIG_SOC_EXYNOS7885) += exynos7885-universal7885.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
