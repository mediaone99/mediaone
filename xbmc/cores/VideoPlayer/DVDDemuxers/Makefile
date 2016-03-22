INCLUDES+=-I/Users/Ninja/mediaone/mediaone/xbmc/cores/VideoPlayer

SRCS  = DemuxMultiSource.cpp
SRCS += DVDDemux.cpp
SRCS += DVDDemuxBXA.cpp
SRCS += DVDDemuxCDDA.cpp
SRCS += DVDDemuxFFmpeg.cpp
SRCS += DVDDemuxClient.cpp
SRCS += DVDDemuxUtils.cpp
SRCS += DVDDemuxVobsub.cpp
SRCS += DVDDemuxCC.cpp
SRCS += DVDFactoryDemuxer.cpp

LIB = DVDDemuxers.a

include /Users/Ninja/mediaone/mediaone/Makefile.include
-include $(patsubst %.cpp,%.P,$(patsubst %.c,%.P,$(SRCS)))

