##################################
# Storage lib configuration file #
##################################

cmake_minimum_required (VERSION 2.6)

add_library(Storage SHARED storage.c)
target_link_libraries (Storage jansson)
