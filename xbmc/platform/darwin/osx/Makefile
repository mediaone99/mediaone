.SUFFIXES : .mm

SRCS = SDLMain.mm

LIB=sdlmain.a

include /Users/Ninja/mediaone/mediaone/Makefile.include
-include $(patsubst %.m,%.P,$(patsubst %.mm,%.P,$(patsubst %.cpp,%.P,$(patsubst %.c,%.P,$(SRCS)))))
