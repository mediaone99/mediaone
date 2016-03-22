.SUFFIXES : .m .mm .cpp

SRCS = posix/MessagePrinter.cpp
SRCS += xbmc.cpp
SRCS += XbmcContext.cpp

ifeq ($(findstring osx,x86-osx), osx)
SRCS += darwin/AutoPool.mm
SRCS += darwin/DarwinUtils.mm
SRCS += darwin/DictionaryUtils.mm
SRCS += darwin/DarwinNSUserDefaults.mm
SRCS += darwin/osx/HotKeyController.m
SRCS += darwin/OSXGNUReplacements.c
SRCS += darwin/osx/OSXTextInputResponder.mm
SRCS += darwin/osx/smc.c
SRCS += darwin/osx/XBMCHelper.m
SRCS += darwin/osx/CocoaInterface.mm
endif

LIB=platform.a

include /Users/Ninja/mediaone/mediaone/Makefile.include
-include $(patsubst %.m,%.P,$(patsubst %.mm,%.P,$(patsubst %.cpp,%.P,$(patsubst %.c,%.P,$(SRCS)))))
