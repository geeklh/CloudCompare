
target_sources( ${PROJECT_NAME}
    PRIVATE
        ${CMAKE_CURRENT_LIST_DIR}/LASOpenDlg.h
        ${CMAKE_CURRENT_LIST_DIR}/LASFilter.h
        ${CMAKE_CURRENT_LIST_DIR}/LASFields.h
        ${CMAKE_CURRENT_LIST_DIR}/qPDALIO.h
)

target_include_directories( ${PROJECT_NAME}
	PRIVATE
	    ${CMAKE_CURRENT_SOURCE_DIR}
)
