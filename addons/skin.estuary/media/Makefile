TARGET=Textures.xbt
TARGET_CURIAL=curial.xbt
TARGET_GREEN=green.xbt
TARGET_ORANGE=orange.xbt
TARGET_PINK=pink.xbt
TARGET_MAROON=maroon.xbt
TARGET_CHARCOAL=charcoal.xbt

all: TEXTURES

.PHONY: force

TEXTURES:
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input . -output $(TARGET)
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input ../themes/curial -output $(TARGET_CURIAL)
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input ../themes/green -output $(TARGET_GREEN)
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input ../themes/orange -output $(TARGET_ORANGE)
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input ../themes/pink -output $(TARGET_PINK)
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input ../themes/maroon -output $(TARGET_MAROON)
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input ../themes/charcoal -output $(TARGET_CHARCOAL)

clean:
	rm -f $(TARGET)
	rm -f $(TARGET_CURIAL)
	rm -f $(TARGET_GREEN)
	rm -f $(TARGET_ORANGE)
	rm -f $(TARGET_PINK)
	rm -f $(TARGET_MAROON)
	rm -f $(TARGET_CHARCOAL)

distclean: clean
