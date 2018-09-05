cmake_minimum_required(VERSION 2.6)

SET(POSHLIB_SRCS
	posh.c
	posh.h)

ADD_LIBRARY(posh STATIC ${POSHLIB_SRCS})

install ( TARGETS posh DESTINATION lib )
install ( FILES posh.h DESTINATION include )
