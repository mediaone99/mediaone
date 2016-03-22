TARGET=Textures.xbt

all: $(TARGET)

.PHONY: force

$(TARGET):
	/Users/Shared/xbmc-depends/buildtools-native/bin/TexturePacker -dupecheck -input . -output $(TARGET)

clean:
	rm -f $(TARGET)

distclean: clean

