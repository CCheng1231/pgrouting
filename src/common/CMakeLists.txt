SET(PACKAGE_SQL_FILES "")
ADD_SUBDIRECTORY(sql)
SET(PACKAGE_SQL_FILES "${PACKAGE_SQL_FILES}" PARENT_SCOPE)
#MESSAGE("core/common: ${PACKAGE_SQL_FILES}")
SUBDIRS(doc src test)
