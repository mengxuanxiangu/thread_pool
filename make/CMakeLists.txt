CMAKE_MINIMUM_REQUIRED (VERSION 2.8)
#project name
PROJECT(ThreadPool)
INCLUDE_DIRECTORIES(include)

#source directory
AUX_SOURCE_DIRECTORY(./../src DIR_SRCS)

ADD_EXECUTABLE("./../bin/thread_poll" ${DIR_SRCS})
