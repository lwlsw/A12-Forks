include $(THEOS)/makefiles/common.mk

BUNDLE_NAME = NtSpeedSettings
NtSpeedSettings_FILES = NtSpeedSettingsController.mm
NtSpeedSettings_INSTALL_PATH = /Library/PreferenceBundles
NtSpeedSettings_FRAMEWORKS = UIKit QuartzCore CoreGraphics MessageUI Social Twitter
NtSpeedSettings_PRIVATE_FRAMEWORKS = Preferences
NtSpeedSettings_CFLAGS = -fobjc-arc
NtSpeedSettings_LDFLAGS = -Wl,-segalign,4000
NtSpeedSettings_ARCHS = armv7 armv7s arm64 arm64e
export ARCHS = armv7 armv7s arm64 arm64e

include $(THEOS_MAKE_PATH)/bundle.mk
