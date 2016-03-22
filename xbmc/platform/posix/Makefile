.SUFFIXES : .m .mm .cpp

SRCS  = main.cpp

LIB=posix.a

include /Users/Ninja/mediaone/mediaone/Makefile.include
-include $(patsubst %.mm,%.P,$(patsubst %.cpp,%.P,$(patsubst %.c,%.P,$(SRCS))))
