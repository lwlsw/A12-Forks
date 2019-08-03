ARCHS = armv7 armv7s arm64 arm64e
THEOS_BUILD_DIR = Packages

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = TokeTime
TokeTime_FILES = Tweak.xm
TokeTime_FRAMEWORKS = UIKit
TokeTime_FRAMEWORKS += CoreGraphics
TokeTime_FRAMEWORKS += QuartzCore

include $(THEOS_MAKE_PATH)/tweak.mk

after-install::
	install.exec "killall -9 SpringBoard"
