INCLUDES+=-I/Users/Ninja/mediaone/mediaone/xbmc/cores/VideoPlayer

CXXFLAGS+=-DHAVE_MMX

SRCS  = DVDAudioCodecFFmpeg.cpp
SRCS += DVDAudioCodecPassthrough.cpp

LIB=Audio.a

include /Users/Ninja/mediaone/mediaone/Makefile.include
-include $(patsubst %.cpp,%.P,$(patsubst %.c,%.P,$(SRCS)))

