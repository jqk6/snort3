
set( FILE_LIST
    smtp.cc
    smtp.h
    smtp_paf.cc
    smtp_paf.h
    smtp_util.cc
    smtp_util.h
    smtp_xlink2state.cc
    smtp_xlink2state.h
    smtp_config.h
    smtp_module.cc
    smtp_module.h
    smtp_normalize.cc
    smtp_normalize.h
)

if (STATIC_INSPECTORS)
    add_library( smtp STATIC ${FILE_LIST})

else (STATIC_INSPECTORS)
    add_shared_library(smtp inspectors ${FILE_LIST})

endif (STATIC_INSPECTORS)
