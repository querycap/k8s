VERSION=$(shell cat Dockerfile.version | grep "^FROM " | sed -e "s/FROM.*:v\{0,\}//g" )

DOCKERX_NAME ?= heapster
DOCKERX_TAGS ?= $(VERSION)
DOCKERX_BUILD_ARGS ?= VERSION=$(VERSION)

include ../Makefile