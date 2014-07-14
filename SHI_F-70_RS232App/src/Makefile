TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += SHI_F-70_RS232

# xxxRecord.h will be created from xxxRecord.dbd
#DBDINC += xxxRecord
# install SHI_F-70_RS232.dbd into <top>/dbd
DBD += SHI_F-70_RS232.dbd

# specify all source files to be compiled and added to the library
#SHI_F-70_RS232_SRCS += xxx

SHI_F-70_RS232_LIBS += $(EPICS_BASE_IOC_LIBS)

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

