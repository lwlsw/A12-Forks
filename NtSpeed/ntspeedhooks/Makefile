include $(THEOS)/makefiles/common.mk

TWEAK_NAME = NtSpeed
NtSpeed_FILES = Tweak.xm
NtSpeed_FRAMEWORKS = CydiaSubstrate Foundation UIKit CoreGraphics
#NtSpeed_CFLAGS = -fobjc-arc
NtSpeed_LDFLAGS = -Wl,-segalign,4000

NtSpeed_ARCHS = armv7 armv7s arm64 arm64e
export ARCHS = armv7 armv7s arm64 arm64e

include $(THEOS_MAKE_PATH)/tweak.mk
	
	
all::
	