TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES

#----------------------------------------------------
# Create and install (or just install) into <top>/db
# databases, templates, substitutions like this
DB += depo-plc-di.db
DB += depo-plc-do.db
#DB += depo-plc-ai.db
#DB += depo-plc-ao.db

DB += test.db
DB += depo-plc-write.db
DB += depo-plc.db
DB += depo-plc-ai-calc.db
DB += depo-plc-pt-calc.db
DB += depo-plc-gv.db

DB_INSTALLS += $(EPICS_BASE)/db/asynRecord.db
DB_INSTALLS += $(EPICS_BASE)/db/iocAdminSoft.db

#----------------------------------------------------
# If <anyname>.db template is not named <anyname>*.template add
# <anyname>_template = <templatename>

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

